# XDAT Editor — L2JA.L.N

Pacote **pronto para usar** do editor de **`Interface.xdat`** para Lineage 2. Não é necessário compilar: extraia a pasta e execute o launcher.

**Repositório:** [github.com/ALN2025/editor-xdat-l2jaln](https://github.com/ALN2025/editor-xdat-l2jaln)

---

## Requisitos

| Item | Detalhe |
|------|---------|
| **Java** | **JDK 8** com **JavaFX** incluído |
| **Sugestão** | [Azul ZuluFX 8](https://www.azul.com/downloads/?version=java-8-lts&package=jdk-fx) ou `winget install Azul.ZuluFX.8.JDK` |

> Um JDK 8 “genérico” **sem JavaFX** costuma falhar ao abrir a interface. Use uma distribuição **FX** (ZuluFX, Liberica Full, etc.).

---

## Como usar

1. Baixe o repositório (**Code → Download ZIP**) ou clone com Git.
2. **Não apague** as pastas `bin` e `lib`.
3. Dê duplo clique em **`Iniciar XDAT Editor L2JA.LN.bat`**.

Instruções rápidas também estão em **`LEIAME.txt`** na raiz desta pasta.

---

## Estrutura da pasta

```
├── bin/          ← scripts gerados pelo Gradle (entrada do editor)
├── lib/          ← bibliotecas e .jar do editor
├── LEIAME.txt
├── Iniciar XDAT Editor L2JA.LN.bat
└── README.md
```

---

## Créditos

- Editor baseado no projeto [**xdat_editor**](https://github.com/acmi/xdat_editor) (acmi e contribuidores).
- Este repositório (**L2JA.L.N**) apenas empacota uma **build** para facilitar quem não quer compilar o *source*.

---

## Licença e uso

Respeite a licença do projeto original. Este pacote é oferecido **como está**, para fins de edição de interface em ambientes de servidor privado / estudo, conforme a política da tua comunidade e da lei aplicável.
