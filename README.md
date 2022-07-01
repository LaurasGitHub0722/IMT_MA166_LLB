# IMT_MA166_LLB
Entwicklung eines Deep Learning Systems zur Erkennung von chirurgischen Prozessschritten für die automatisierte Dokumentation

Der Code wurde von Jin et al. übernommen und auf meine Arbeit angepasst. Es wird nur der Phasenzweig verwendet. 

Citation:

@article{jin2020multi,
  title={Multi-task recurrent convolutional network with correlation loss for surgical video analysis},
  author={Jin, Yueming and Li, Huaxia and Dou, Qi and Chen, Hao and Qin, Jing and Fu, Chi-Wing and Heng, Pheng-Ann},
  journal={Medical image analysis},
  volume={59},
  pages={101572},
  year={2020},
  publisher={Elsevier}
}



Setup & Training

Pytorch 1.2.0+

1. Preprosessing: Videos in Frames zerlegen und auf 250x250 bzw 128x128 verkleinern
2. get_paths_labels ausführen, um Datenset aus Label und Frame zu erstellen
3. train_singlenet_phase ausführen, um das Netz zu trainieren
4. test_singlenet_phase ausführen, um das Netz zu testen
5. Prediction ausführen, um eine Textdatei mit der Vorhersage zu erhalten
