# VanGoghGAN
Group project for [Data Mining Master's Course 2020-2021](https://corsidilaurea.uniroma1.it/it/view-course-details/2020/30430/20200313105820/e8bf4052-6615-4294-8317-fd28b44a5677/7e61218e-0da7-4c0a-acb3-ead6cfcd1cf8/ebc2faa2-f8de-483f-94f4-19fbfa794a0e/1718a47a-b62b-4d44-96b9-97ed0684d10c?guid_cv=7e61218e-0da7-4c0a-acb3-ead6cfcd1cf8&current_erogata=e8bf4052-6615-4294-8317-fd28b44a5677) at Sapienza Università di Roma.

### Team members
Felice Massotti ([Felixmassotti](https://github.com/Felixmassotti))

Daniela Moretti ([danymrt](https://github.com/danymrt))

Redemptor Jr Laceda Taloma ([jrtaloma](https://github.com/jrtaloma))

## Abstract
During his life Van Gogh left many unfinished sketches of landscapes. Our initial task was to paint these sketches with the intention of creating paintings never
made with a style as faithful as possible to that of Van Gogh. His famous style belongs to the movement of Post-Impressionism, with strong and decisive colors and
brushstrokes. However during his life he approached different movements, including Impressionism. For this reason our initial task was more complicated, because
it was not easy to find an appropriate dataset that could train the GAN in a correct way. So, finally, we have decided to relax the task and paint the sketches of
a whole artistic current, not only one artist. In this way we have included artworks by more than 20 impressionists to enlarge the dataset.

## Dataset
2840 landscapes by 24 artists collected from [wikiart.org](https://www.wikiart.org/).

**Boudin**: 145,
**Caillebotte**: 58,
**Cezanne**: 110,
**Chase**: 62,
**Corot**: 219,
**Gauguin**: 153,
**Gorbatov**: 43,
**Guillaumin**: 40,
**Hassam**: 135,
**Korovin**: 22,
**Loiseau**: 158,
**Martin**: 112,
**Maufra**: 81,
**Metcalf**: 83,
**Monet**: 483,
**Pissarro**: 123,
**Renoir**: 39,
**Robinson**: 22,
**Rose**: 65,
**Shishkin**: 110,
**Sisley**: 168,
**Thaulow**: 15,
**Twachtman**: 32,
**Van Gogh**: 344.

181 original drawings by Van Gogh and realists
**Van Gogh**: 134,
**Realists**: 47.

The source code of the project, datasets (Dataset, DatasetStyle, Test) and final results are hosted on Google Drive as the work is developed with Google Colab notebooks.

**Link to Google Drive**: [https://drive.google.com/drive/folders/1CyEVFwQLJfaclPvtuMpgNR8CQ9SzetV1?usp=sharing](https://drive.google.com/drive/folders/1CyEVFwQLJfaclPvtuMpgNR8CQ9SzetV1?usp=sharing)

## Methods
[**Pix2Pix**](https://github.com/brakes312t4/VanGoghGAN/blob/main/Notebooks/Pix2Pix.ipynb)

[**Label-Supervised Pix2Pix**](https://github.com/brakes312t4/VanGoghGAN/blob/main/Notebooks/StylePix2Pix.ipynb)

[**CycleGAN**](https://github.com/jrtaloma/VanGoghGAN/blob/main/Notebooks/CycleGAN.ipynb)
