Pytorch implementation (using pretrained weights) of:

    Color image demosaicking via deep residual learning,
    Tan, Runjie and Zhang, Kai and Zuo, Wangmeng and Zhang, Lei
    2017 IEEE International Conference on Multimedia and Expo (ICME)

based on [CDM-CNN](https://github.com/csrjtan/CDM-CNN)

This code was created to reproduce the results of CDM-CNN for this publication

    T. Ehret, and G. Facciolo, "A Study of Two CNN Demosaicking Algorithms", 
    Image Processing On Line, 9 (2019), pp. 220–230. https://doi.org/10.5201/ipol.2019.274

Example call (result is saved as output.png):

    python3 ./cdmcnn.py --input input.png --output output.png
