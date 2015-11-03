#Estrutura de Pasta em Ruby

'''
README
Rakefile
app/
config/
db/
doc/
lib/
log/
public/
script/
test/
tmp/
vendor/
'''


README – arquivo com instruções de uso;
Rakefile – script de construção;

app/ – Dentro dessa pasta estão os arquivos da estrutura MVC – (Model, View e Controller);

components/ – componentes reutilizáveis;

config/ – parâmetros de configurações tanto do projeto quanto do banco de dados;

db/ – Informações sobre o esquema e as migrations geradas para modificar o banco de dados;

doc/ – Documentação auto gerada, utilizando o Rdoc,

lib/ – Código compartilhado códigos que não podemos adicionar a uma um modelo, view ou controller, algo como um gerador de arquivos pdf.

log/ – documentos de log produzidos pelo seu aplicativo;

public/ – Diretório acessível pela Web. É a pasta onde o HTTP server utiliza pra rodar o seu aplicativo;
script/ – Scripts utilitários, onde estão os programas utilizados pelos desenvolvedores Rails, para entede-los você pode executalos sem nenhum argumento, você obterá informações sobre de uso;
test/ – Utilitários de testes, onde escrevemos os teste funcionais, testes de integração, fixtures e simulações;
tmp/ – Arquivos temporários utilizados e gerados em tempo de execução do seu aplicativo;
vendor/ – Código importado onde você irá por os seus plugins utilizados pela aplicação, código de terceiros# comecando-Ruby
