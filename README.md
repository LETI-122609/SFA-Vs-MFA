# Autenticação Simples vs. Autenticação Multifator: Segurança baseada no risco e no perfil do utilizador

## Sobre o projeto

Este projeto é desenvolvido no âmbito da unidade curricular **Segurança em Redes e Sistemas de Informação**, do **Mestrado em Engenharia de Telecomunicações e Informática**, no Iscte.

O trabalho tem como objetivo analisar as diferenças entre a **Autenticação de Fator Único (SFA — Single-Factor Authentication)** e a **Autenticação Multifator (MFA — Multi-Factor Authentication)**, avaliando as suas características, vantagens, limitações e adequação a diferentes contextos de utilização.

Pretende-se compreender em que situações a implementação de MFA é necessária ou recomendada, considerando o nível de risco, a sensibilidade da informação protegida e o perfil dos utilizadores. O trabalho procura também analisar o equilíbrio entre segurança, facilidade de utilização e acessibilidade.

## Objetivos

- Compreender o funcionamento da SFA e da MFA.
- Comparar os dois modelos de autenticação em termos de segurança e usabilidade.
- Analisar a importância da MFA na proteção de contas e recursos digitais.
- Estudar as necessidades de diferentes perfis de utilizadores, incluindo utilizadores comuns e pessoas idosas.
- Identificar tecnologias e mecanismos utilizados na implementação de MFA.
- Avaliar as vantagens, limitações e adequação de cada tecnologia a diferentes cenários.

## Estrutura do relatório

O relatório está organizado nas seguintes áreas principais:

1. **Tipos de Autenticação** - 
2. **Autenticação Simples e Autenticação Multifator** — apresentação dos conceitos, mecanismos de funcionamento e fatores de autenticação.
3. **Comparação entre SFA e MFA** — análise das diferenças em termos de segurança, facilidade de utilização, implementação e experiência do utilizador.
4. **Utilidade e necessidade da MFA** — avaliação da necessidade de autenticação multifator em função do risco e dos recursos protegidos.
5. **Diferentes perfis de utilizadores** — análise das necessidades e dificuldades de diferentes grupos de utilizadores.
6. **Exemplos práticos e tecnologias** — estudo de tecnologias como TOTP, FIDO2, WebAuthn, notificações push, códigos de utilização única, smart cards e autenticação biométrica.
7. **Conclusões** — síntese dos resultados e recomendações sobre a utilização de MFA em diferentes contextos.

## Tecnologias e mecanismos analisados

| Tecnologia | Descrição |
|---|---|
| **TOTP** | Geração de códigos temporários de utilização única. |
| **FIDO2 e WebAuthn** | Autenticação baseada em credenciais criptográficas, incluindo passkeys e chaves de segurança. |
| **Notificações push** | Aprovação de pedidos de autenticação através de aplicações móveis. |
| **SMS e correio eletrónico** | Receção de códigos de utilização única para verificação da identidade. |
| **Smart Cards** | Cartões inteligentes utilizados na autenticação através de credenciais ou certificados digitais. |
| **Biometria** | Utilização de características físicas, como impressão digital ou reconhecimento facial. |

## Organização dos ficheiros

O relatório é desenvolvido em LaTeX, permitindo organizar o conteúdo por secções e facilitar a colaboração entre os elementos do grupo.

Exemplo de organização dos ficheiros:

```text
.
├── main.tex
├── indice.tex
├── introducao.tex
├── referencias.bib
├── imagens/
│   └── LOG_ISCTE_PRETO.jpg
└── README.md
```

- `main.tex`: ficheiro principal, responsável pela configuração e compilação do relatório.
- `indice.tex`: conteúdo relativo ao índice, caso seja gerido separadamente.
- `introducao.tex`: secção de introdução.
- `referencias.bib`: referências bibliográficas, caso seja utilizado BibTeX.
- `imagens/`: diretório destinado às imagens utilizadas no documento.
- `README.md`: descrição do projeto e da sua organização.

A estrutura apresentada é ilustrativa e pode ser ajustada à organização efetiva do repositório.

## Compilação do relatório

Para compilar o relatório, pode ser utilizado o [Overleaf](https://www.overleaf.com/) ou uma instalação local de LaTeX.

O ficheiro principal é `main.tex`. A compilação deve ser efetuada a partir desse ficheiro, garantindo que os restantes ficheiros incluídos através de `\input{}` ou `\include{}` se encontram nos caminhos corretos.

## Referências

As fontes bibliográficas utilizadas incluem documentação técnica, normas de segurança, artigos científicos e publicações relevantes sobre autenticação e cibersegurança.

Entre as fontes de referência encontram-se:

- [NIST — Glossário de Single-Factor Authentication](https://csrc.nist.gov/glossary/term/single_factor)
- [NIST — Digital Identity Guidelines: Authentication and Authenticator Management](https://csrc.nist.gov/pubs/sp/800/63/b/4/final)
- [Das et al. (2019) — Why Don’t Elders Adopt Two-Factor Authentication? Because They Are Excluded by Design](https://academic.oup.com/innovateage/article/3/Supplement_1/S325/5617506)

## Elementos do grupo

- Duarte Sá
- Tiago Nobre
- Martim Teixeira
- Henrique Lopes
- João Matos

## Unidade curricular

**Segurança em Redes e Sistemas de Informação**  
Mestrado em Engenharia de Telecomunicações e Informática  
Iscte — Instituto Universitário de Lisboa
