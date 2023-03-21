# Sophoappeal appeal prediction dnn transferlearning
DNN transfer learning experiment for appeal prediction for sophoappeal.

This repository is part of [Sohpappeal](https://github.com/Telecommunication-Telemedia-Assessment/sophoappeal).
Please use the main repository as starting point.
**Using the main repository is highly recommended, because the analysis scripts relies on other data in the parent folder.**

This repository is part of the DFG project [Sophoappeal (437543412)](https://www.tu-ilmenau.de/universitaet/fakultaeten/fakultaet-elektrotechnik-und-informationstechnik/profil/institute-und-fachgebiete/fachgebiet-audiovisuelle-technik/forschung/dfg-projekt-sophoappeal), it contains images and analysis scripts.


## Requirements

* python3, python3-pip, git, imagemagick, wget
* jupyterlab with scikit-learn, tensorflow

## Scripts

* all `retrain_XYZ.py` scripts are for the retraining of a specific DNN.
* `check_results.ipynb` is a script to evaluate the prediction performance.
* `deeper_retrain_inception_v3.py` is a variant of the retraining script to also consider more layers of the Inception V3 model.


## Acknowledgments

If you use this software or data in your research, please include a link to the repository and reference the following paper.

```bibtex
@article{goering2023imageappeal,
  title={Image Appeal Revisited: Analysis, new Dataset and Prediction Models},
  author={Steve G\"oring and Alexander Raake},
  journal={IEEE Access},
  year={2023},
  publisher={IEEE},
  note={to appear}
}
```

## License
GNU General Public License v3. See [LICENSE.md](./LICENSE.md) file in this repository.

