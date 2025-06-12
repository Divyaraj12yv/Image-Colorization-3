# Image-Colorization-3

🔍 Project Highlights :-
🕰️ Era-Based Colorization: Colorization adapts based on the selected historical period.

🧠 Deep Learning Model: Built using architectures like InstColorization or Zhang et al.'s Model (2016), fine-tuned for historical domains.

📚 Historical Datasets: Trained and evaluated using curated collections of authentic grayscale photos from the 1920s, WWII, and more.

⚙️ No GUI Required: Focused on functionality and accuracy. Optional CLI/GUI lets users select a historical period.

📈 Evaluation Metrics: PSNR and SSIM used for performance evaluation with historical color references.

🎯 Objective 
Colorize black-and-white photographs from different historical periods.

Preserve historical accuracy in tone, clothing, and background color representations.

(Optional) Support user selection of historical era for model variation.

🧠 Model Used
DeOldify is an open-source deep learning model built on PyTorch. It leverages:

A NoGAN training approach

A ResNet-based generator

A critic discriminator to improve image realism

📁 Dataset
A collection of grayscale historical photographs, primarily from:

World War II (1939–1945)

1920s vintage collections

The dataset includes portraits, streetscapes, and documentary scenes. These help the model generalize colorization across time periods.

For better historical color reproduction, DeOldify was optionally fine-tuned on this dataset (if training was performed).
