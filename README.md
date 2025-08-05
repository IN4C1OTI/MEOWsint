MEOWsint (Multifunctional Extraction OSINT With style 😼) é uma ferramenta de OSINT (Inteligência de Código Aberto) desenvolvida em Python, com interface em terminal (CLI) interativa, rápida e estilosa — com tema de gatinho 🐱.

Ideal para profissionais de cibersegurança, entusiastas de OSINT, estudantes e pesquisadores.

✨ Funcionalidades Atuais
📍 Consulta de Endereços: busca por CEP com detalhes de logradouro, cidade e estado.

🌐 Consulta de IP: geolocalização e dados técnicos de IPv4 ou IPv6.

🕵️ Domínios: informações sobre sites, WHOIS e servidor.

🧍 Pessoas:

CPF (formato realista, com proteção aos dados)

CNPJ

E-mail (validação)

Telefone (validação e operadora)

🚗 Veículos: consulta de placas (mock)

🖼️ Busca reversa de imagem (em desenvolvimento).

👤 Redes sociais: localização de perfis por nome de usuário.

🧠 Nome completo (mock/local por enquanto).

💾 Exportação de resultados em .json e .txt.

🕓 Histórico de buscas local, com opção de limpeza.

🎨 Interface com digitação animada e variações de cor no terminal.

⚙️ Tecnologias Utilizadas
Python 3.12+

requests — Requisições HTTP

rich — Interface bonita no terminal

os, json, random, time — Operações de sistema e organização

Estrutura modular por categoria

📦 Instalação
bash
Copiar
Editar
git clone https://github.com/seuusuario/MEOWsint.git
cd MEOWsint
pip install -r requirements.txt
python main.py
⚠️ Python 3.12 ou superior é recomendado.

📁 Estrutura do Projeto
bash
Copiar
Editar
MEOWsint/
├── consultas/
│   ├── cep.py
│   ├── ip.py
│   ├── dominio.py
│   ├── cpf.py
│   ├── cnpj.py
│   ├── email.py
│   ├── telefone.py
│   ├── redes.py
│   ├── nome.py
│   └── placa.py
├── utilitarios/
│   ├── exportar.py
│   ├── historico.py
│   └── menu.py
├── main.py
└── requirements.txt
🧪 Exemplos de Uso
bash
Copiar
Editar
[MEOWsint 🐾] Selecione uma opção:

1. Consultar CEP
2. Consultar IP
3. Consultar Domínio
...
Resultado de uma consulta:

yaml
Copiar
Editar
[✓] Resultado encontrado:
- Cidade: São Paulo
- Bairro: Vila Mariana
- Estado: SP
  
📌 Status de Desenvolvimento
Módulo	Status
CEP	✅ Pronto
IP	✅ Pronto
Domínio	✅ Pronto
CPF	⚠️ Em desenvolvimento (mock)
CNPJ	✅ Funcional
E-mail	✅ Funcional
Telefone	✅ Funcional
Nome	⚠️ Em desenvolvimento (mock)
Placa	⚠️ Em desenvolvimento (mock)
Redes Sociais	✅ Funcional
Busca reversa de imagem	🚧 Em breve

🐱 Créditos
Desenvolvido por Marcos Inácio com foco em aprendizado, análise OSINT e ética no uso de informações públicas.
