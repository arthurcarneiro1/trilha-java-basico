# 📱 Desafio DIO - Componente iPhone

Este projeto implementa a modelagem de um iPhone com suas 3 principais funcionalidades:

- 🎵 Reprodutor Musical  
- 📞 Aparelho Telefônico  
- 🌐 Navegador de Internet  

## 📊 Diagrama UML

```mermaid
classDiagram
    class ReprodutorMusical {
        +tocar()
        +pausar()
        +selecionarMusica(String musica)
    }

    class AparelhoTelefonico {
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }

    class NavegadorInternet {
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }

    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
```

## 📁 Estrutura

```
ReprodutorMusical.java  
AparelhoTelefonico.java  
NavegadorInternet.java  
iPhone.java
```

## ✅ Requisitos Atendidos

- [x] Diagramar em UML
- [x] Criar interfaces
- [x] Implementar classe `iPhone`