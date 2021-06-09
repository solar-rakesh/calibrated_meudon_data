# calibrated_meudon_data
This repository contains calibrated (rotation and shift corrected) Carrington maps created from hand-drawn maps of Meudon archive (available from Solar Survey Archive at Observatoire de Paris: http://bass2000.obspm.fr/lastsynmap.php). The Meudon archive consists of grayscale images for Carrington rotation 876-1823 and coloured images for Carrington rotation 1824-2008. Missing rotations include {993, 1033, 1044, 1186, 1275, 1851-1930}. We have used an automated method (described in our paper: https://arxiv.org/pdf/2106.04320.pdf) to calibrate these maps and utilised the resulting maps for further studies of solar filaments. Each calibrated map is in the Carrington longitude (x) vs latitude (y) grid and covers 360 degrees along x and 180 degrees along y. We are making these calibrated maps public now and can be used for any further studies only after citing our paper Mazumder et al 2021.

@misc{mazumder2021solar,
      title={Solar Cycle Evolution of Filaments over a Century: Investigations with the Meudon and McIntosh Hand-drawn Archives}, 
      author={Rakesh Mazumder and Subhamoy Chatterjee and Dibyendu Nandy and Dipankar Banerjee},
      year={2021},
      eprint={2106.04320},
      archivePrefix={arXiv},
      primaryClass={astro-ph.SR}
}
