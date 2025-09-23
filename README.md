function enviarWhatsApp(e) {
  var resposta = e.values; // todas as respostas da linha
  var nome = resposta[1];  // Nome completo (coluna B)
  var cidade = resposta[2]; // Cidade/Estado (coluna C)
  var telefone = resposta[3]; // WhatsApp com DDD (coluna D)
  var horario = resposta[4]; // Melhor horário (coluna E)

  var mensagem = "🚀 Nova aplicação recebida!\n\n" +
    "👤 Nome: " + nome + "\n" +
    "📍 Cidade/Estado: " + cidade + "\n" +
    "📱 WhatsApp informado: " + telefone + "\n" +
    "⏰ Melhor horário: " + horario + "\n\n" +
    "👉 Verifique mais detalhes na planilha.";

  // SEU NÚMERO FIXO (você pode trocar para o seu WhatsApp)
  var meuNumero = "5549998110445"; // coloque sempre com DDI 55 + DDD + número
  var url = "https://wa.me/" + meuNumero + "?text=" + encodeURIComponent(mensagem);

  // Abre a URL (gera a mensagem no WhatsApp)
  UrlFetchApp.fetch(url);
}

// Ativar o gatilho
function criarGatilho() {
  ScriptApp.newTrigger("enviarWhatsApp")
    .forSpreadsheet(SpreadsheetApp.getActiveSpreadsheet())
    .onFormSubmit()
    .create();
}
