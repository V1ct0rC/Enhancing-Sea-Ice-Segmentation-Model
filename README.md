# Enhancing Sea Ice Segmentation Model: Exploring Neural Network Ensembles and Optimization Strategies for Improved Performance

> Bruno Henrique dos Santos Marques <br>
> José Vinicius de Santana Souza <br>
> Victor Gabriel de Carvalho <br>

<p align="justify">
Polar ice, covering approximately 10% of Earth's surface and holding nearly 70% of freshwater, profoundly impacts climate and socioeconomic systems. Accurate sea ice segmentation using computer vision techniques is crucial for understanding climate change implications. This project focuses on enhancing a UNet-based segmentation model using a dataset of polar ice images. Various optimization techniques including hyperparameter tuning, ensemble methods like bagging, and pre-trained models such as ResNet18 were explored. Results show ResNet18 outperforming other models in Intersection over Union (IoU), Dice Coefficient, and Pixel Accuracy. Challenges including limited GPU access on Google Colab affected model performance, particularly for optimization methods. Despite challenges, ensemble models demonstrated promising results, reducing prediction variance. This study underscores the importance of robust segmentation techniques for monitoring polar ice dynamics in a changing climate.
</p>

---

<p align="justify">
This project consists of four implementation files, a PDF report and a PDF presentation. Each .ipynb implementation follows an optimization approach (pre-training, ensembling and Optuna parameterization). The results are compared in the last notebook. For more information, please read the report.
</p>