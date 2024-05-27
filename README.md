
```mermaid
classDiagram
    class ReprodutorMusical {
        +void tocar()
        +void pausar()
        +void selecionarMusica(String musica)
    }

    class AparelhoTelefonico {
        +void ligar(String numero)
        +void atender()
        +void iniciarCorreioVoz()
    }

    class NavegadorInternet {
        +void exibirPagina(String url)
        +void adicionarNovaAba()
        +void atualizarPagina()
    }

    class iPhone {
        +public void tocar()
        +public void pausar()
        +public void selecionarMusica(String musica)
        +public void ligar(String numero)
        +public void atender()
        +public void iniciarCorreioVoz()
        +public void exibirPagina(String url)
        +public void adicionarNovaAba()
        +public void atualizarPagina()
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet

