# Framework testes de Api automatizados 
Projeto de testes de Api automatizados com Ruby e HTTParty



## Inicialização
Para o desenvolvimento dessa aplicação de teste, foram utilizadas as seguintes ferramentas:
1.  [Ruby](https://rubyinstaller.org/)
2.	[Cucumber](https://cucumber.io/)
3.  [HTTParty](https://rubygems.org/gems/httparty/)
4.	[Rspec](https://github.com/rspec/rspec)
5.  [Git](https://git-scm.com/download/win)

### Pré requisitos
Necessário instalar o [Ruby](https://rubyinstaller.org/) na versão mais recente e em seguida rodar os comandos através terminal:

```
gem install bundler --force
```

### Instalação
>Clone o projeto no diretório de interesse e abra o terminal dentro da pasta do projeto:
```
git clone <url-clone-projeto>
url: https://github.com/avillaafabricio/Framework-Api-Ruby.git
```
>Execute o comando abaixo para realizar a instalação das dependencias:
```
bundle install
```

# Executando os Testes
>Após a instalação das dependências e configuração do ambiente, vamos executar os testes:
```
cucumber -t @tag -p [ambiente]
Ex.: cucumber -t @tag -p dev
```


Obs.: Apoio para desenvolvimento do Framework: Qarentena, Iterasys