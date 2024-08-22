# DreamCinema: Cinematic Transfer with Free Camera and 3D Character

[**Paper**](https://arxiv.org/abs/2403.09625) | [**Project Page**](https://liuff19.github.io/DreamCinema//) | [**Video**](https://liuff19.github.io/DreamCinema/)

Official implementation of DreamCinema: Cinematic Transfer with Free Camera and 3D Character

Weiliang Chen, [Fangfu Liu](https://liuff19.github.io/), Diankun Wu, Haowen Sun, Haixu Song, [Yueqi Duan](https://duanyueqi.github.io/)


<p align="center"> All Code will be released soon... 🏗️ 🚧 🔨</p>

Abstract: *We are living in a flourishing era of digital media, where everyone has the potential to become a personal filmmaker. Current research on cinematic transfer empowers filmmakers to reproduce and manipulate the visual elements (\eg cinematography and character behaviors) from classic shots. However, characters in the reimagined films still rely on manual crafting, which involves significant technical complexity and high costs, making it unattainable for ordinary users. Furthermore, their estimated cinematography lacks smoothness due to inadequate capturing of inter-frame motion and modeling of physical trajectories. Fortunately, the remarkable success of 2D and 3D AIGC has opened up the possibility of efficiently generating characters tailored to users' needs, diversifying cinematography. In this paper, we propose \textbf{DreamCinema}, a novel cinematic transfer framework that pioneers generative AI into the film production paradigm, aiming at facilitating user-friendly film creation. Specifically, we first extract cinematic elements (\ie human and camera pose) and optimize the camera trajectory. Then, we apply a character generator to efficiently create 3D high-quality characters with a human structure prior. Finally, we develop a structure-guided motion transfer strategy to incorporate generated characters into film creation and transfer it via 3D graphics engines smoothly. Extensive experiments demonstrate the effectiveness of our method for creating high-quality films with free camera and 3D characters. *

<p align="center">
    <img src="assets/teaser.png">
</p>


## Cinematic Transfer Results

DreamCinema generates diverse characters with high quality and alignment to user preferences and selectively transfer these cinematic behavior (e.g. cinematography and character motions) to the new characters.
<p align="center">
    <img src="assets/main_results.png">
</p>






## BibTeX

```bibtex
;; @misc{liu2024makeyour3d,
;;       title={Make-Your-3D: Fast and Consistent Subject-Driven 3D Content Generation}, 
;;       author={Fangfu Liu and Hanyang Wang and Weiliang Chen and Haowen Sun and Yueqi Duan},
;;       year={2024},
;;       eprint={2403.09625},
;;       archivePrefix={arXiv},
;;       primaryClass={cs.CV}
}
```
