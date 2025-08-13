<div align="center">
<h1 align="center" >
  TexVerse: A Universe of 3D Objects <br> with High-Resolution Textures
</h1>

  <a href='#'><img src='https://img.shields.io/badge/Project%20Page-Coming%20Soon-lightgrey'></a> &nbsp;
  <a href='https://raw.githubusercontent.com/yiboz2001/TexVerse/main/assets/TexVerse.pdf'><img src='https://img.shields.io/badge/Paper-Download-critical'></a> &nbsp;
<br>
  <a href='https://huggingface.co/datasets/YiboZhang2001/TexVerse'>
  <img src='https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-TexVerse-blue'></a> &nbsp;
  <a href='https://huggingface.co/datasets/YiboZhang2001/TexVerse-1K'>
  <img src='https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-TexVerse--1K-blue'></a> &nbsp;
  <a href='https://huggingface.co/datasets/YiboZhang2001/TexVerse-Skeleton-Animation'>
  <img src='https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-TexVerse--Skeleton--Animation-blue'></a> &nbsp;
<br>
**[Yibo Zhang<sup>1,2</sup>](https://yiboz2001.github.io/),  [Li Zhang<sup>1,3</sup>](https://lzrobots.github.io/),  [Rui Ma<sup>2 &ast;</sup>](https://ruim-jlu.github.io/), [Nan Cao<sup>1,4</sup>](http://nancao.org/)** 
<br>
<sup>1</sup>Shanghai Innovation Institute
<sup>2</sup>Jilin University 
<sup>3</sup>Fudan University 
<sup>4</sup>Tongji University 
<br>
&ast; Corresponding Author

</div>

![TexVerse](assets/teaser.png)

**TexVerse is a large-scale 3D dataset featuring high-resolution textures.**  Its key characteristics include:

1. **Scale & Source**: TexVerse dataset has **858,669 unique 3D models** curated from Sketchfab, including **158,518** with physically based rendering (PBR) materials.
2. **Variants**: Each model includes all high-resolution variants, resulting in a total of **1,659,097 3D instances**.
3. **Specialized Subsets**:
   For the rigged and animated categories of models, we further obtain the original user-uploaded file format to prevent the loss of skeletons and animations during the format conversion of Sketchfab. 
   - **TexVerse-Skeleton**: **69,138 rigged models**.
   - **TexVerse-Animation**: **54,430 animated models**.

   Note: We only successfully downloaded the source files for 87,414 models. For details, please refer to `model_paths.txt` in [TexVerse-Skeleton-Animation](https://huggingface.co/datasets/YiboZhang2001/TexVerse-Skeleton-Animation).
4. **Annotations**: Detailed model annotations covering overall characteristics, structural components, and fine-grained features.



Feel free to contact me ([ybzhang23@mails.jlu.edu.cn](mailto:ybzhang23@mails.jlu.edu.cn)) or open an issue if you have any questions or suggestions.


## News

- [2025-08-11] We have released the **TexVerse** dataset. Feel free to download it.

## Statistics

![TexVerse](assets/statistics.png)

## Metadata

We provide the following metadata files.
- **TexVerse Dataset**  
  - Object ID list: `./metadata/TexVerse_id_list.txt`  
  - PBR material model ID list: `./metadata/TexVerse_pbr_id_list.txt`  
  - Dataset metadata: `metadata.json` in [**TexVerse**](https://huggingface.co/datasets/YiboZhang2001/TexVerse).
  - Annotations for a subset of 856,312 objects: `caption.json` in [**TexVerse**](https://huggingface.co/datasets/YiboZhang2001/TexVerse).
- **TexVerse-Animation Dataset**  
  - Animated object ID list: `./metadata/TexVerse-Animation_id_list.txt`  
- **TexVerse-Skeleton Dataset**  
  - Rigged object ID list: `./metadata/TexVerse-Skeleton_id_list.txt`  

## Download

#### **TexVerse Dataset**  
Due to the file number limitations of the Hugging Face repository:  
- The **2K**, **4K**, and **8K** resolution data are hosted in [**TexVerse**](https://huggingface.co/datasets/YiboZhang2001/TexVerse).  
- The **1K** resolution data are hosted separately in [**TexVerse-1K**](https://huggingface.co/datasets/YiboZhang2001/TexVerse-1K).  

#### **TexVerse-Animation Dataset** and **TexVerse-Skeleton Dataset**  
Jointly hosted in [**TexVerse-Skeleton-Animation**](https://huggingface.co/datasets/YiboZhang2001/TexVerse-Skeleton-Animation).


## License

Individual objects in TexVerse are all licensed as creative commons distributable objects. The metadata will provide the license for each object.

- [CC BY](https://creativecommons.org/licenses/by/4.0/): 699,075  
- [CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/): 88,710  
- [CC BY-SA](https://creativecommons.org/licenses/by-sa/4.0/): 14,624  
- [CC BY-NC](https://creativecommons.org/licenses/by-nc/4.0/): 31,514  
- [CC BY-NC-ND](https://creativecommons.org/licenses/by-nc-nd/4.0/): 11,599  
- [CC BY-ND](https://creativecommons.org/licenses/by-nd/4.0/): 7,008  
- [CC0](https://creativecommons.org/publicdomain/zero/1.0/): 6,139 

## Citation

```
@article{zhang2025texverse,
  title     = {TexVerse: A Universe of 3D Objects with High-Resolution Textures},
  author    = {Zhang, Yibo and Zhang, Li and Ma, Rui and Cao, Nan}, 
  journal   = {arXiv preprint},
  year      = {2025}
}
```







