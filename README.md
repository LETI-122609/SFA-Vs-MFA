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

1. **Tipos de Autenticação** -  apresentação das diferentes categorias de fatores de autenticação.
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
| **SMS** | Receção de códigos de utilização única para verificação da identidade. |
| **Smart Cards** | Cartões inteligentes utilizados na autenticação através de credenciais ou certificados digitais. |
| **Biometria** | Utilização de características físicas, como impressão digital ou reconhecimento facial. |

## Organização dos ficheiros

O relatório é desenvolvido em LaTeX, permitindo organizar o conteúdo por secções e facilitar a colaboração entre os elementos do grupo, organizando dos ficheiros da seguinte forma:

```text
.
├── Imagens/
│   └── LOG_ISCTE_PRETO.jpg
├── capa.tex
├── conclusoes.tex
├── desenvolvimento.tex
├── glossario.tex
├── Indice.tex
├── Introducao.tex
├── main.tex
├── referencias.tex
├── resumo.tex
└── README.md
```

- `Imagens/`: diretório destinado às imagens utilizadas no documento.
- `capa.tex`: capa do relatório.
- `conclusoes.tex`: secção onde é feita a conclusão do relatório.
- `desenvolvimento.tex`: secção onde o tema é desenvolvido em vários pontos.
- `glossario.tex`: glossário onde são explicados certos termos/siglas importantes.
- `Indice.tex`: conteúdo relativo ao índice, caso seja gerido separadamente.
- `Introducao.tex`: secção de introdução do relatório.
- `main.tex`: ficheiro principal, responsável pela configuração e compilação do relatório.
- `referencias.tex`: referências bibliográficas.
- `resumo.tex`: resumo do relatório.
- `README.md`: descrição do projeto e da sua organização.

A estrutura apresentada é ilustrativa e pode ser ajustada à organização efetiva do repositório.

## Compilação do relatório

Para compilar o relatório, pode ser utilizado o [Overleaf](https://www.overleaf.com/) ou uma instalação local de LaTeX.

O ficheiro principal é `main.tex`. A compilação deve ser efetuada a partir desse ficheiro, garantindo que os restantes ficheiros incluídos através de `\input{}` ou `\include{}` se encontram nos caminhos corretos.

## Referências

As fontes bibliográficas utilizadas incluem documentação técnica, normas de segurança, artigos científicos e publicações relevantes sobre autenticação e cibersegurança.

Entre as fontes de referência encontram-se:

1. [https://csrc.nist.gov/glossary/term/single_factor](https://csrc.nist.gov/glossary/term/single_factor)
2. [https://www.techtarget.com/cybersecurity/definition/single-factor-authentication-SFA](https://www.techtarget.com/cybersecurity/definition/single-factor-authentication-SFA)
3. [https://www.cgd.pt/Site/Saldo-Positivo/formacao-e-tecnologia/Pages/dados-biometricos.aspx](https://www.cgd.pt/Site/Saldo-Positivo/formacao-e-tecnologia/Pages/dados-biometricos.aspx)
4. [https://techterms.com/pt/definition/hard_token](https://techterms.com/pt/definition/hard_token)
5. [https://www.mdpi.com/1999-5903/15/4/146](https://www.mdpi.com/1999-5903/15/4/146)
6. [https://www.cisa.gov/secure-our-world/turn-mfa](https://www.cisa.gov/secure-our-world/turn-mfa)
7. [https://www.hsgac.senate.gov/media/reps/portman-presses-president-and-ceo-of-colonial-pipeline-on-gaps-in-cybersecurity-practices/](https://www.hsgac.senate.gov/media/reps/portman-presses-president-and-ceo-of-colonial-pipeline-on-gaps-in-cybersecurity-practices/)
8. [https://academic.oup.com/innovateage/article/3/Supplement_1/S325/5617506](https://academic.oup.com/innovateage/article/3/Supplement_1/S325/5617506)
9. [https://academic.oup.com/iwc/article-abstract/22/3/153/693231](https://academic.oup.com/iwc/article-abstract/22/3/153/693231)
10. [https://www.ndss-symposium.org/wp-content/uploads/2017/09/01_5-paper.pdf](https://www.ndss-symposium.org/wp-content/uploads/2017/09/01_5-paper.pdf)
11. [https://www.science-gate.com/IJAAS/Articles/2025/2025-12-06/1021833ijaas202506001.pdf](https://www.science-gate.com/IJAAS/Articles/2025/2025-12-06/1021833ijaas202506001.pdf)
12. [https://arxiv.org/pdf/2010.00339](https://arxiv.org/pdf/2010.00339)
13. [https://security.googleblog.com/2019/05/new-research-how-effective-is-basic.html?m=1](https://security.googleblog.com/2019/05/new-research-how-effective-is-basic.html?m=1)
14. [https://www.microsoft.com/research/publication/how-effective-is-multifactor-authentication-at-deterring-cyberattacks/](https://www.microsoft.com/research/publication/how-effective-is-multifactor-authentication-at-deterring-cyberattacks/)
15. [https://security.googleblog.com/2019/05/new-research-how-effective-is-basic.html](https://security.googleblog.com/2019/05/new-research-how-effective-is-basic.html)
16. [https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf)
17. [https://www.cisa.gov/sites/default/files/publications/fact-sheet-implement-number-matching-in-mfa-applications-508c.pdf](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implement-number-matching-in-mfa-applications-508c.pdf)
18. [https://csrc.nist.gov/pubs/sp/800/63/b/4/final](https://csrc.nist.gov/pubs/sp/800/63/b/4/final)
19. [https://csrc.nist.gov/pubs/fips/201-3/final](https://csrc.nist.gov/pubs/fips/201-3/final)

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
