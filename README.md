# Equine articular cartilage

[Dataset on equine cartilage near infrared spectra, composition, and 
functional properties](https://www.nature.com/articles/s41597-019-0170-y)
by Jaakko K. Sarin, Jari Torniainen, Mithilesh Prakash, Lassi Rieppo, 
Isaac O. Afara & Juha Töyräs contains NIRS measurements from 869 
different locations across the articular surfaces of five equine fetlock joints.

The [nirs_and_references_revised.flow](nirs_and_references_revised.flow) ADAMS
workflow loads the Matlab dataset (`nirs_and_references_revised.mat`), calculates 
the average of the three spectra per sample, and generates the following files:

* one `.spec` file per sample (as used by [ADAMS](https://adams.cms.waikato.ac.nz/) for spectral data)
* one `.arff` file with all the samples as used by [WEKA](https://www.cs.waikato.ac.nz/ml/weka/)
* one `.csv` file with all the samples


## Downloads

* [2022.12.15](https://github.com/spectral-datasets/equine-articular-cartilage/releases/tag/v2022.12.15)

  * [.mat](https://github.com/spectral-datasets/equine-articular-cartilage/releases/download/v2022.12.15/nirs_and_references_revised.mat)
  * [.arff.gz](https://github.com/spectral-datasets/equine-articular-cartilage/releases/download/v2022.12.15/nirs_and_references_revised.arff.gz)
  * [.csv.gz](https://github.com/spectral-datasets/equine-articular-cartilage/releases/download/v2022.12.15/nirs_and_references_revised.csv.gz)
  * [.spec](https://github.com/spectral-datasets/equine-articular-cartilage/releases/download/v2022.12.15/nirs_and_references_revised.zip) (as one zip file)


## Links

* [Publication](https://www.nature.com/articles/s41597-019-0170-y)
* [Dataset](https://springernature.figshare.com/articles/dataset/Near_infrared_spectroscopic_measurements_of_equine_articular_cartilage_and_a_set_of_biomechanical_compositional_and_structural_reference_values_/7803845?backTo=/collections/Dataset_on_equine_cartilage_near_infrared_spectra_composition_and_functional_properties/4423139)
* [Matlab scripts](https://github.com/UEF-BBC/sarin-scientific-data-2019)


## License

* Dataset: [CC0](https://creativecommons.org/publicdomain/zero/1.0/)
* Matlab scripts: [GPLv3](https://opensource.org/licenses/GPL-3.0)
* ADAMS flow: [MIT](https://opensource.org/licenses/MIT)
