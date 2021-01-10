# Car-Make-Model-verification-system


Questo progetto è stato realizzato per il corso di Machine Learning tenuto all’università degli studi di Salerno. Lo scopo del progetto consiste nel classificare correttamente la marca ed il modello di un’automobile, in particolare date due immagini contenenti un’auto, stabilire se queste fossero dello stesso modello e marca.
Per la risoluzione del task è stato usato un approccio con le Deep Neural Network basato su una architettura nota come “siamese model”.

<p align="center">
  <img src="https://github.com/AndreaMontillo/Car-Make-Model-verification-system/blob/main/immagini/siamese.png" width="350" title="hover text">
</p>
 
Il dataset utilizzato, “VMMRdb”, contiene circa 300.000 immagini ed è stato preprocessato attraverso tecniche classiche di data Augmentation come Rotation, Translation, Noise injection, etc.

Come preprocessing è stata utilizzata anche la terza versione dell’algoritmo YOLO per effettuare il detection della macchina all’interno dell’immagine.
Al termine dell’addestramento sono state raggiunte performance del 95.8% circa sul test set utilizzato per la valutazione in ottica dell’esame.

<p align="center">
  <img src="https://github.com/AndreaMontillo/Car-Make-Model-verification-system/blob/main/immagini/car1.png" width="200" title="hover text">
  <img src="https://github.com/AndreaMontillo/Car-Make-Model-verification-system/blob/main/immagini/car2.png" width="200" alt="accessibility text">
</p>

<p align="center">
  <img src="https://github.com/AndreaMontillo/Car-Make-Model-verification-system/blob/main/immagini/dataset.png" width="650" title="hover text">
</p>


