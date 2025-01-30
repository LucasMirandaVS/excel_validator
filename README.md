# Validação de Planilhas Excel
Programa em Python que faz a ingestão e validação de arquivos xlsx com uma interface gráfica desenvolvida usando Streamlit.
O programa ingere as planilhas e valida se a estrutura está condizente com o padrão necessário e depois salva em um  banco de dados POSTRGRES.

### Link do Projeto
https://excel-validator.onrender.com

Obs: Se atentar a estrutura de planilha que o programa aceita:
```bash
email: EmailStr
data: datetime
valor: PositiveFloat
produto: str
quantidade: PositiveInt
categoria: CategoriaEnum
```


### Instalação e Configuração

1. Clone o repositório:
```bash
git clone git@github.com:LucasMirandaVS/excel_validator.git
cd dataprojectstarterkit
```
2. Configure a versão correta do Python com `pyenv`:
```bash
pyenv install 3.11.5
pyenv local 3.11.5
```
3. Instale as dependências do projeto:
```bash
python -m venv .venv
# O padrao é utilizar .venv
source .venv/bin/activate
# Usuários Linux e mac
.venv\Scripts\Activate
# Usuários Windows
pip install -r requirements.txt  
```