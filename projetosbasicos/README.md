




## Python environmen

### pyenv 
(gerencia versões python dos projetos) 

<code>
pyenv --version 
#[versão do pyenv]
pyenv --versions 
[versões python dos projetos]
pyenv install 3.x.x 
[instala uma versão do python para uso]
pyenv local 3.11.1 
[seleciona a versão do python para o projeto]
pyenv global 3.11.4 
[seleciona a versão global  do python]
</code>

### PIP 

<code>
pip list 
pip install 
--limpar o pip 
pip uninstall
python.exe -m pip install --upgrade pip

</code>


### PIPX 
instala pacotes por usuario na maquina local 

<code>
pip install pipx 

</code>

### ipython  
(Melhor visualização do python puro no CMD)

<code>
pipx install ipython 
-- ADD C:\Users\junin\.local\bin nas variaveis de ambiente 

</code>



### Poetry  
(Gestão de dependencias de pacote) 

<code>
pipx install poetry

(configurar o poetry para gerenciar os ambientes virtual )


poetry config virtualenvs.in-project true


<\code>

## NOVO PROJETO

<code>
poetry new projeto-streamlit

cd projeto-streamlit

poetry env local 3.12.4

poetry env use 3.12.4

poetry add pandas

poetry add streamlit

-- Abre no VSCODE
code .

poetry shell 

</code>



## Comandos uteis GIT 

<code>
#git init 
#git config --global user.email "email@gmai.com"
#git congig --global user.name "jorgemoraes"
#git add .\main.py
#git commit -m "meu primeiro commit"
#git log
</code>


install Git 

ssh-keygen -t ed25519 -C "jdemoraes.jr@gmail.com"



Kaggle 
-- Data Sets Free para estudos
