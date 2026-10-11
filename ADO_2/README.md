# Leis de Newton e Aplicações: simulação interativa

**Aluno:** VICTOR ELEUTERIO TRINDADE (RA - 1140439717)
**Disciplina:** Mecânica e Física Moderna, Ciência da Computação

**Abrir a simulação:** https://eleuteriotrindade.github.io/Repo-Fisica/ADO_2

Página web (HTML e JavaScript, sem instalar nada) com os três sistemas do enunciado, escolhidos pelo menu "Sistema". O gráfico e os resultados atualizam assim que os controles são movidos.

1. **Plano inclinado com atrito e tração**: controles de m1, m2, θ e μ (μs = μk). Mostra aceleração, tração no fio e se o sistema está em movimento ou em equilíbrio estático. Gráfico de x(t) e v(t) pelo MRUV.
2. **Força centrípeta**: controles de R, v e m, com a massa girando na tela. Mostra ω e Fc. Extensão opcional "carro em curva plana" com controle de μ e cálculo de v máx = √(μgR).
3. **Força de arrasto**: arrasto linear ou quadrático, com controles de m, coeficiente (b ou c, conforme o modo) e tempo máximo. Compara com a queda livre (v = g·t) e mostra a velocidade terminal pela fórmula e o tempo para atingir 95% dela.

Nenhuma integração numérica é usada. Todas as grandezas vêm das fórmulas fechadas do enunciado, avaliadas sobre um vetor de tempo. Os comentários no código (`index.html`) indicam de onde vem cada fórmula.
