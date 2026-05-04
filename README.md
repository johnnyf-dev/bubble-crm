# 📘 Documentação Técnica — Mini CRM de Contatos (Bubble.io)

## 🎯 Objetivo
Criar um Mini CRM básico para cadastro e gerenciamento de contatos, permitindo que qualquer usuário (sem necessidade de login) preencha um formulário, salve contatos no banco de dados do Bubble (SaaS) e visualize ou exclua registros em tempo real.  
✨ O título do CRM foi animado para dar um pouco de vida à interface.

---

## 🛠️ Tecnologias Utilizadas
- **Bubble.io** (NoCode, workflows, banco de dados SaaS interno)  
- **API Connector (planejado)** para futura integração com ViaCEP  
- **GitHub** — documentação e versionamento  
- **IA agentes** — suporte autodidata para resolução de problemas  

---

## 📂 Estrutura do Formulário
- **Inputs:** Nome, E-mail, Telefone (validado), CEP, Endereço, Notas.  
- **Botões:** Salvar Contato, Excluir.  
- **Alertas:**  
  - Campos obrigatórios vazios  
  - E-mail inválido  
  - Sucesso ao salvar  

---

## 📊 Workflows Configurados
- **Animação do título** → balança ao clicar  
- **Salvar contato** → valida campos obrigatórios, grava no banco, exibe alerta de sucesso, limpa inputs  
- **Mostrar alerta de campos vazios** → impede gravação  
- **Validação de e-mail em tempo real** → alerta de erro  
- **Excluir contato** → remove registro da célula atual no Repeating Group  

---

## 📸 Espaço para Screenshots
*(Substitua os links abaixo pelos caminhos reais das imagens após subir no GitHub)*

- Formulário de cadastro  
  ![Formulário de Cadastro](images/formulario.png)

- Alertas de erro e sucesso  
  ![Alertas](images/alertas.png)

- Lista dinâmica de contatos (Repeating Group)  
  ![Lista de Contatos](images/lista_contatos.png)

- Exclusão de contato em tempo real  
  ![Exclusão](images/exclusao.png)

---

## 🚀 Próximos Passos
- Configurar **Privacy Rules** para permitir criação/exclusão sem login  
- Integrar **ViaCEP API** para preenchimento automático de endereço  
- Evoluir para **multiusuário** com Supabase (planejado)  
- **Adição de alertas estratégicos para melhorar a experiência**  
- Automação futura com **Make/Zapier**  

---

## 🧩 Desafios Superados
- Recuperação de regras de privacidade apagadas  
- Aprendizado rápido em regex e workflows  
- Implementação de feedback visual claro (alertas de erro e sucesso)  

---

## ⏱️ Tempo Investido
Total: **~16 horas** (incluindo planejamento, estrutura, workflows, validações, ajustes visuais e documentação)  

---

## 🌐 Link do Projeto
https://johnnyfdev.bubbleapps.io/version-test/cadastro_de_usuarios_1_5?debug_mode=true


------------------------

# 📘 Technical Documentation — Mini CRM Contacts (Bubble.io)

## 🎯 Objective
Create a basic Mini CRM for contact registration and management, allowing any user (no login required) to fill out a form, save contacts in Bubble’s SaaS database, and view or delete records in real time.  
✨ The CRM title was animated to bring some life to the interface.

---

## 🛠️ Technologies Used
- **Bubble.io** (NoCode, workflows, internal SaaS database)  
- **API Connector (planned)** for future ViaCEP integration  
- **GitHub** — documentation and version control  
- **AI agents** — self-learning support for problem solving  

---

## 📂 Form Structure
- **Inputs:** Name, Email, Phone (validated), ZIP Code, Address, Notes.  
- **Buttons:** Save Contact, Delete.  
- **Alerts:**  
  - Required fields empty  
  - Invalid email  
  - Success when saving  

---

## 📊 Configured Workflows
- **Title animation** → shakes when clicked  
- **Save contact** → validates required fields, saves to database, shows success alert, resets inputs  
- **Show empty fields alert** → prevents saving  
- **Real-time email validation** → error alert  
- **Delete contact** → removes record from the current cell in the Repeating Group  

---

## 📸 Screenshots
*(Replace the links below with the actual paths to your images once uploaded to GitHub)*

- Registration form  
  ![Registration Form](images/registration_form.png)

- Error and success alerts  
  ![Alerts](images/alerts.png)

- Dynamic contact list (Repeating Group)  
  ![Contact List](images/contact_list.png)

- Real-time deletion  
  ![Deletion](images/deletion.png)

---

## 🚀 Next Steps
- Configure **Privacy Rules** to allow creation/deletion without login  
- Integrate **ViaCEP API** for automatic address filling  
- Evolve to **multi-user** with Supabase (planned)  
- **Strategic alerts added to improve the user experience**  
- Future automation with **Make/Zapier**  

---

## 🧩 Challenges Overcome
- Recovery of deleted privacy rules  
- Quick learning in regex and workflows  
- Implementation of clear visual feedback (error and success alerts)  

---

## ⏱️ Time Invested
Total: **~16 hours** (including planning, structure, workflows, validations, visual adjustments, and documentation)  

---

## 🌐 Project Link
https://johnnyfdev.bubbleapps.io/version-test/cadastro_de_usuarios_1_5?debug_mode=true
