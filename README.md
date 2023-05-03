# inertial-atk
This is a temporary repository for testing inertial odometry against attacks.

---

The proposed model consists of two modules trained using a model-based approach. It is necessary to train the first module (or stage) before training the second one.

---

Before proceeding to the training step, install my Python module using the following command:

`pip install ptk-patrickctrf`

---

To train the first stage, run the following command:

`python train_first_inertial_stage.py`

The code is commented line-by-line, and the EuRoC and TUM datasets are already included in the repository.
