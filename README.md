# Geometric Shapes Classification

<img src="https://images.pexels.com/photos/7307621/pexels-photo-7307621.jpeg" alt="shapes"/>

Geometric Shapes Classification represents an advanced image classification model that integrates vision and language encoding. This model is fine-tuned from the google/siglip2-base-patch16-224 architecture specifically for the purpose of multi-class shape recognition. Utilizing the SiglipForImageClassification framework, it effectively classifies a variety of geometric shapes.

## The Model Categorizes

- 0: Circle ◯
- 1: Kite ⬰
- 2: Parallelogram ▰
- 3: Rectangle ▭
- 4: Rhombus ◆
- 5: Square ◼
- 6: Trapezoid ⏢
- 7: Triangle ▲

## Classification Summary

```bash
                 precision    recall  f1-score   support

       Circle ◯     0.9921    0.9987    0.9953      1500
         Kite ⬰     0.9927    0.9927    0.9927      1500
Parallelogram ▰     0.9926    0.9840    0.9883      1500
    Rectangle ▭     0.9993    0.9913    0.9953      1500
      Rhombus ◆     0.9846    0.9820    0.9833      1500
       Square ◼     0.9914    0.9987    0.9950      1500
    Trapezoid ⏢     0.9966    0.9793    0.9879      1500
     Triangle ▲     0.9772    0.9993    0.9881      1500

       accuracy                         0.9908     12000
      macro avg     0.9908    0.9908    0.9907     12000
   weighted avg     0.9908    0.9908    0.9907     12000
```
