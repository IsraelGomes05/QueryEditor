<html>
  <body>
    <a class="badge-align" href="https://www.codacy.com/app/IsraelGomes05/QueryEditor?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=IsraelGomes05/QueryEditor&amp;utm_campaign=Badge_Grade"><img src="https://api.codacy.com/project/badge/Grade/95f3f209a11c441d8d33849caadb88a2"/></a>
    <h2>QueryEditor</h2>
    <h4>Editor de querys para aplicações java Desktop</h4>
    <p>
      Este é um editor de querys simples, para aplicações java Desktop, suporta todos os bancos de dados. utilizando conexões JDBC.
      Ideal para ambientes onde é necessário executar consultas direto da maquina do cliente. 
    </p>
    <h2>Features</h2>
    <ul>
      <li>Mapeamento do banco de dados (Tabelas e colunas)</li>
      <li>Histórico de querys com buscador</li>
      <li>Exportação para Excel</li>
      <li>Compatibilade com qualquer BD</li>
      <li>Multiplas Abas</li>
      <li>Leve</li>
    </ul>
    <h2>Visão Geral</h2>
    <img src="https://github.com/IsraelGomes05/QueryEditor/blob/master/QueryEditor/imgs/tela-principal.PNG">
    <h2>Como Usar</h2>
   
<h4>Crie uma Instância da Classe QueryTelaPrincipla Passando como paramentro O Frame que será associado, Se é modal ou não, conexão com BD, Local do arquivo com as querys (Histórico)</h4>
  <code>QueryTelaPrincipal query = new QueryTelaPrincipal(this, true, ConnectionFactory.getConexao(), "C:/Users/Israel         Gomes/Documents/teste.txt");<br>
    query.setVisible(true);
 </code>
   </body>
</html>

