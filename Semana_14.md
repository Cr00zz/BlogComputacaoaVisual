<h2>Diferenças entre tex1 * tex2 e mul(tex1, tex2)</h2>

<p>Para o caso da função mul(tex1, tex2) as imagens de entrada não possuem canais de cor compatíveis, então resultado da multiplicação será uma imagem completamente branca, ou seja, todos os pixels terão valores iguais a 255. Por exemplo, se img1 for uma imagem em escala de cinza (com um único canal de cor) e img2 for uma imagem colorida (com três canais de cor), o resultado da multiplicação será uma imagem completamente branca. Isso já não acontece no caso de tex1 * tex2, em que é feita uma multiplicação de matrizes básica sem depender de outros dados.</p>

![image](https://github.com/Cr00zz/BlogComputacaoaVisual/assets/64552061/c3eabad7-008a-4487-9901-a0d0fe53db1a)

![image](https://github.com/Cr00zz/BlogComputacaoaVisual/assets/64552061/3f1740de-fb3d-461c-83b0-674b486299a8)
