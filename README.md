# 🌱 Sementes da Prosperidade

> Aplicativo iOS para motivação e desenvolvimento pessoal, com áudios inspiradores, resumos e reflexões diárias.  

---

## ✨ Visão Geral
O *Sementes da Prosperidade* é um app de crescimento pessoal desenvolvido em *Swift (iOS)*.  
Ele disponibiliza:
- 🎧 *Áudios motivacionais* exclusivos  
- 📝 *Resumos e pontos-chave*  
- 💡 *Reflexões diárias* para hábitos de prosperidade  
- ☁️ Integração com *Firebase* para armazenamento e distribuição de conteúdo  

---

## 🚀 Tecnologias
- *Swift 5+*  
- *UIKit* (MVP inicial, com plano de migração para SwiftUI)  
- *Arquitetura Limpa* (Domain / Data / Presentation)  
- *Firebase* (Auth, Firestore, Storage)  
- *AVFoundation* para player de áudio  

---

## 📂 Estrutura do Projeto

SementesDaProsperidade/
 ├── SementesDaProsperidade/   # Código fonte principal
 │   ├── AppDelegate.swift
 │   ├── SceneDelegate.swift
 │   ├── Home/
 │   │   ├── View/
 │   │   ├── ViewModel/
 │   │   └── Model/
 │   └── Shared/               # Utilitários e componentes comuns
 │
 ├── Resources/                # Assets, fontes, JSON, áudios
 ├── Tests/                    # Unit Tests
 ├── UITests/                  # UI Tests
 ├── README.md
 ├── .gitignore
 └── LICENSE


---

## 🛠️ Como rodar localmente
1. Clone o repositório:
    `git clone https://github.com/AlexandreBCardoso/SeedsProsperity.git`
   
2. Abra o projeto no Xcode:
    `open SeedsProsperity.xcodeproj`
   
3. Execute no simulador ou device físico:
   
   ⌘ + R
   

---

## 🔧 Funcionalidades Planejadas (Roadmap)
- [x] 🎧 Player de áudios integrado com Firebase Storage  
- [ ] 📝 Resumos e pontos-chave exibidos junto ao áudio  
- [ ] 🌅 Reflexão diária (notificações locais)  
- [ ] 📥 Cache offline de conteúdos  
- [ ] 🧩 Migração gradual para SwiftUI  

---

## 📸 Telas (em breve)
(Adicione screenshots ou mockups aqui)  

---

## 🔹 Configurar boas práticas de commits
Adote um padrão de mensagens (exemplo **Conventional Commits**):

- `feat:` nova funcionalidade  
- `fix:` correção de bug  
- `docs:` alteração em documentação  
- `refactor:` refatoração de código  
- `style:` ajustes de formatação  
- `test:` testes adicionados ou ajustados  

Exemplo:
    `git commit -m "feat(audio): add audio player with clean architecture"`

---

## 🤝 Contribuição
Contribuições são bem-vindas!  
1. Faça um fork do projeto  
2. Crie uma branch de feature: `git checkout -b feature/nova-funcionalidade`
3. Commit suas mudanças: `git commit -m "feat: descrição da feature"`
4. Push para a branch: `git push origin feature/nova-funcionalidade`
5. Abra um Pull Request  

---

## 📜 Licença
Este projeto está sob a licença [MIT](LICENSE).