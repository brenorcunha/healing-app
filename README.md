
# HealingAPP

 Aplicativo WEB para gestão médica que conecta pacientes e profissionais de forma prática eficiente.
 Desenvolvido com Python e Django 5, o APP oferece uma solução completa para agendamento, gestão de prontuários e organização da rotina clínica.

![Logo](https://onedrive.live.com/embed?resid=5D154344EF67B72B%2160051&authkey=%21AINk-0eBPXOM684&width=77&height=77)

## Autores

- [@brenorcunha](https://www.github.com/brenorcunha)

## Recursos

- Responsividade (Funciona em dispositivos móveis), interface intuitiva, Ssegurança de dados com autenticação integrada.
- Gerenciamento de usuários (Registro, login, agendamento de consulta, cancelamento de consulta, entre outros).
- Gerenciamento para médicos (Registro, login, disponibilização das consultas, Gerenciamento de agenda, gerenciamento de arquivos, como atestados, receitas e demais importantes).
- Dashboard (Retorna o gráfico do padrão das consultas dos 7 últimos dias para o profissional logado).

## Screenshots

![Login Page](https://onedrive.live.com/embed?resid=5D154344EF67B72B%2159976&authkey=%21AAHpDjVm3Nvq2Xk&width=660)
![Homepage -Patients](https://onedrive.live.com/embed?resid=5D154344EF67B72B%2160058&authkey=%21AIHWg53cxODxgsI&width=660)
![User consultations](https://onedrive.live.com/embed?resid=5D154344EF67B72B%2160061&authkey=%21AJWEBmEpP0NmyH8&width=660)
![Medical register](https://onedrive.live.com/embed?resid=5D154344EF67B72B%2159980&authkey=%21AP8acmDpz5XgV5s&width=660)
![Dr's open agenda](https://onedrive.live.com/embed?resid=5D154344EF67B72B%2160059&authkey=%21AI4aBP1l0dI9fyg&height=656)
![Dr's appointments](https://onedrive.live.com/embed?resid=5D154344EF67B72B%2160057&authkey=%21ABqaWDbuzru_4D0&height=656)
![Patients -Available consultations](https://onedrive.live.com/embed?resid=5D154344EF67B72B%2160062&authkey=%21APwc7QD1-l-vjTg&width=660)
![Dr's dashboard](https://onedrive.live.com/embed?resid=5D154344EF67B72B%2160060&authkey=%21AJQukG3DVt7syCc&width=660>)

## Roadmap

- [X] Implementação das telas de login e registro.
- [X] Integração com banco de dados SQLite3.
- [X] Agendamento e cancelamento de consultas.
- [X] Upload de arquivos e documentos médicos.
- [X] Dashboard gráfico com estatísticas.
- [X] Testes automatizados.
- [X] Validação de formulário com Django Forms.
- [X] Deploy com plataforma em nuvem.

## 🖥️ Como executar

1. Clone o repositório:

```bash
git clone https://github.com/brenorcunha/healingapp.git
```

2. Crie um ambiente virtual:

```bash
python -m venv venv
source venv/bin/activate  # Linux / MacOS
venv\Scripts\activate      # Windows
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Execute o servidor:

```bash
python manage.py runserver
```

5. Acesse no navegador:

<http://localhost:8000/users/login/>

Disponível em: <https://brenorcunha.pythonanywhere.com/>