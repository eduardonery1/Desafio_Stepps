# Desafio_Stepps
Códigos usados para resolução dos desafios do processo seletivo

## 1. Treine o modelo
Use o train_yolo.ipynb para treinar o modelo yolo necessário

## 2. Track!
Substitua o track.py do repo original pelo arquivo desse repo e instale todas as dependencias.
Depois, execute:

```bash
$ python track.py --yolo-weights your-model.pt --source /path/to/Desafio_Video.mp4 --save-vid  # bboxes + segmentation masks
```

O vídeo gerado terá uma contagem, no canto superior esquerdo, de todos os mamões que tocam a linha amarela.

No desafio da imagem: O modelo encontrou 58 mamões, na pasta Resultados Imagem, encontra-se a imagem com Bounding boxes desenhadas e as labels encontradas

O video gerado do desafio original se encontra nesse link: https://drive.google.com/file/d/1-RP5JN4VOs9DRw_AOpageyesEiLCKcoM/view?usp=share_link
