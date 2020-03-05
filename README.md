# Created a model that can identify sneaker's brand (Nike, Adidas or Reebok) from pictures.
# Deployed [fast.ai](https://www.fast.ai) model on [Render](https://render.com)


Using resnet34 and resnet50, trained a model with 1500 images, it can identify well the brands (Nike, Adidas or Reebok) of a sport sneaker given an picture.
You can test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```
