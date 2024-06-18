classDiagram
    class ReprodutorMusical {
        +tocar()
        +pausar()
        +selecionarMusica(string)
    }

    class AparelhoTelefonico {
        +ligar(string numero)
        +atender(String exemplo)
        +iniciarCorreiovoz
    }

    class NavegadorInternet {
        +exibirpagina(string url)
        +adicionarNovaAba()
        +atualizarPagina()
        
    }

    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet