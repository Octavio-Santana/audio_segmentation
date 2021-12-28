# Audio Segmentation


Vamos considerar o seguinte contexto — imagine que tu se depara com um problema no qual os áudios são do tipo mono, ou seja, tem apenas um único canal, e o seu objetivo é identificar trechos em que cada pessoa está falando e então realizar recortes neste áudio de modo que cada novo áudio gerado corresponda apenas a uma única pessoa falando. Podemos ir um pouco além e considerar que o problema é do tipo analise de satisfação do cliente, mas primeiro temos que recortar trechos do áudio em que a atendente está falando, da mesma forma que o do cliente.


O contexto foi apenas para inspirar, mas neste notebook o que vamos desenvolver de fato é um classificador que identifica os trechos do áudio em que o estudante ou o professor está falando. É um problema análogo, mas o que atacaremos será um pouco mais simples. A base de dados usada está disponível no kaggle, bem como o notebook com a solução completa.


A base de dados para criação e analise do modelo foi retirado do kaggle
https://www.kaggle.com/wiradkp/mini-speech-diarization


Foi escrito um artigo no medium com uma introdução e explicando alguns passos deste notebook. 
https://medium.com/@octaviofisica/segmenta%C3%A7%C3%A3o-de-%C3%A1udio-2f1e978b3d16