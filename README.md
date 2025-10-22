# Análise do Circuito RC 

Este repositório contém a análise experimental de um circuito RC (capacitor + resistor). Os dados foram coletados via monitor serial e comparados com o comportamento teórico de descarga exponencial do capacitor.

## Circuito no TinkerCad
<div style="text-align: center;">
	<img src="assets\circuito-rc.png" alt="Diagrama do circuito" style="width:70%;" />
</div>

&ensp; Link para execução do TinkerCad <a href="https://www.tinkercad.com/things/kk2uaUD1O9W-led-com-botao/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard&sharecode=vnVhcY9amhNMY9ZC8cjsP_c1PZ9SKOAWkjtKoY48Zb4">Link</a>


### Gráfico comparativo
<div style="text-align: center;">
	<img src="assets\graph.png" alt="Gráfico comparativo" style="width:70%;" />
</div>

### Vídeo do circuito real
<div style="text-align: center;">
<img title="Led Interno" src="assets\video.gif" width="700" height="">
</div>

## Conclusão rápida
- As medições confirmam a descarga exponencial do capacitor.
- A soma das tensões Vc + Vr permanece próxima de 5 V, confirmando conservação de tensão.

Para detalhes e plots, confira o notebook `index.ipynb`.