Modell basierend auf vortrainiertem Convolutional Neural Network (CNN)

Verwendet Transfer Learning mit Fine-Tuning, um auf die spezifische Aufgabe, CAPTCHA-Klassifizierung, angepasst zu werden
Basismodell: 
  Modell verwendet EfficientNet-B0, ein vortrainiertes CNN, das ursprünglich für die Klassifikation auf dem ImageNet-Datensatz (1000 Klassen) trainiert wurde
Fine-Tuning: 
  Feature-Extraktion: Die vortrainierten Schichten extrahieren allgemeine Merkmale (z. B. Kanten, Texturen)
  Anpassung an neue Klassen: Die letzte Klassifikationsschicht wird durch eine neue Schicht ersetzt, die auf die spezifische Anzahl der Klassen (num_classes = 12) abgestimmt ist
