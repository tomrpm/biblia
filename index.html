import os
from bottle import Bottle, request, template, debug,route, error, run
import requests

#app = Bottle()
@route('/hello/')
@route('/hello/<name>')
def hello(name='Stranger'):
    return template('Hello {{name}}, how are you?', name=name)
    #return 'Hello World'


@route('/')
def index():
    return '''
     <h1 style="color: #06c1ff;">DEUS SEJA LOUVADO!!!</h1>
    <h1 style="color: #2e6c80;">Receba uma mensagem do senhor:</h1>
    <h2 style="color: #2e6c80;"><a href="msg?tipo=aleatoria" style="background-color: #2b2301; color: #fff; padding: 3px 10px; font-weight: bold; border-radius: 5px;">Clique aqui</a></h2>
    <h2 style="color: #2e6c80;">&nbsp;</h2>



    <p>-----------------------------------------------------</p>
    <div id='conteudo'></div>
    <h2 style="color: #0e1011;">Selecione um apostolo e receba uma mensagem.</h2>
    
    <form action="apostolo" method="POST">
    <select name="selecapostolo" id="tipo">
        <option value="#">Selecione</option>
        <option value="mt">Mateus</option>
         <option value="lc">Lucas</option>
         <option value="sl">Salmos</option>
         <option value="ex">Exôdo</option>
         <option value="gn">Gênesis</option>
    </select> 
    <input value="Enviar" type="submit" />
    </form>
'''
    
@route('/apostolo', method='POST')
@route('/apostolo', method='GET')
def exibe_msg():
    apostolo = str(request.forms.get('raca'))
    msg = str(request.params.get('text'))
    if "aleatoria" in msg:
        response = requests.get('https://www.abibliadigital.com.br/api/verses/nvi/random')
        status = response.json().get("status")
        if "success" in status:
            msg = response.json().get("text");
            return print(%s,msg)<br><br><a href=\"/\">Voltar </a> <br>") 
        else:
            return template("Erro ao buscar a imagem. <br><br><a href=\"/\">Voltar </a>")
    response = requests.get('https://dog.ceo/api/breed/' + raca + '/images/random')
    status = response.json().get("status")
    if "success" in status:
        img = response.json().get("message");
        return template(" <img src=\"{{im}}\" alt=''><br><br><a href=\"/\">Voltar </a> <br>", im=img)    
    

        
@error(404)
def error404(error):
    return 'Página não encontrada.'

#debug(True)  
run(host="0.0.0.0", port=int(os.environ.get("PORT", 5000)))
