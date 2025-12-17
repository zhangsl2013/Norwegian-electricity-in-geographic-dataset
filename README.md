# Norwegian electricity in geographic dataset (NoreGeo)
This repository is about a geographic dataset for the electricity infrastructures, power grids, power plants, power production and consumption, and power resources in Norway in 2024. Interactive maps based on our data is also available.

we present a comprehensive geographic dataset representing the electricity system in Norway. We collect data from multiple authoritative sources, process it into widely accepted formats, and generate interactive maps based on this data. Our dataset includes information for each municipality in Norway for the year 2024, encompassing electricity infrastructure, consumption, renewable and conventional production, main power grid topology, relevant natural resources, and population demographics. This work results in a formatted geographic dataset that integrates diverse informational resources, along with openly released interactive maps. We anticipate that our dataset will alleviate software incompatibilities in data retrieval, and facilitate joint analyses on regional electricity system for energy researchers, stakeholders, and developers.

**Dataset description:** A detailed description of our dataset is available via our [pre-print](https://arxiv.org/pdf/2510.09698).

**Download:** Our dataset can be directly downloaded from Zenodo [here](https://doi.org/10.5281/zenodo.16794604). We store the dataset in Zenodo due to the limited storage quato in Github.

**Code for data processing:** We have openly released the codes for data processing during the dataset generation, available at [our GitHub Gists](https://gist.github.com/slzhang-git)). Particularly, our code illustrates how to convert CRS across for geo-referrenced files [here](https://gist.github.com/slzhang-git/111623cfc55b6604f62e1ebbd6ad1181). We show how to merge numerical solar power production data with its geographical context [here](https://gist.github.com/slzhang-git/9fa8ea6cf8f4d353af576a83d40a7cd3). We show how to inquire the location and area of solar panels by requesting the Overpass Turbo API [here](https://gist.github.com/slzhang-git/b3517e8154657154802e27dec326d08f). We show how to combine daily energy spot price in Norway with its geographical context [here](https://gist.github.com/slzhang-git/7b2bfef7fa26066e65688e1cdc98aeb1). We also show how to convert a tiff file into a GeoJSON file [here](https://gist.github.com/slzhang-git/1cdf65ec6d8cee8ac87a135ccb0cf51e), so that the file can be readily used and easily processed by GIS platforms.

**Citation for our work**:

Shiliang Zhang, Sabita Maharjan, Kai Strunz, Jan Christian Bryne, "Norwegian Electricity in Geographic Dataset (NoreGeo)," _arXiv preprint arXiv:2510.09698_ (2025). [doi: 10.48550/arXiv.2510.09698](https://doi.org/10.48550/arXiv.2510.09698)

BibTex:<br>
@article{zhang2025norwegian,<br>
  title={Norwegian Electricity in Geographic Dataset (NoreGeo)},<br>
  author={Zhang, Shiliang and Maharjan, Sabita and Strunz, Kai and Bryne, Jan Christian},<br>
  journal={arXiv preprint arXiv:2510.09698},<br>
  year={2025}<br>
}

or

Shiliang Zhang, Sabita Maharjan, "Norwegian Electricity in Geographic Dataset (NoreGeo)," _Zenodo_, 2025. [doi: 10.5281/zenodo.16794604](https://doi.org/10.5281/zenodo.16794604).

BibTex:<br>
@dataset{zhang_2025_16794604,<br>
  author={Zhang, Shiliang and Maharjan, Sabita},<br>
  title={Norwegian Electricity in Geographic Dataset (NoreGeo)},<br>
  year=2025,<br>
  publisher={Zenodo},<br>
  doi={10.5281/zenodo.16794604},<br>
  url={https://doi.org/10.5281/zenodo.16794604},<br>
}

**Interactive maps** based on our geographic dataset are publicly avaialbe via ArcGIS Online:

[Norwegian solar power](https://uio-no.maps.arcgis.com/apps/mapviewer/index.html?webmap=469df60bcb374f0b997cf7fd516fc3a6)

[Solar panels in the city of Oslo](https://uio-no.maps.arcgis.com/apps/mapviewer/index.html?webmap=045e64206c874c0eb5bb5e1e2e7cd619)

[Wind resource availability](https://uio-no.maps.arcgis.com/apps/mapviewer/index.html?webmap=2321e585a93f46129d196d3ebe7e7a7f)

[Norwegian wind power](https://uio-no.maps.arcgis.com/apps/mapviewer/index.html?webmap=065d48122dc843bcbdff2593dc055cc7)

[Norwegian hydro power](https://uio-no.maps.arcgis.com/apps/mapviewer/index.html?webmap=b636fc5747ec4e7f8c02f1c9af582990)

[Norwegian daily electricity price 2024](https://uio-no.maps.arcgis.com/apps/mapviewer/index.html?webmap=6c80f11c8411479d8b518f86d90c0048)

[Transformers in Norwegian power system](https://uio-no.maps.arcgis.com/apps/mapviewer/index.html?webmap=71ad265a41804be3a66dff39d24d0548)

[Norwegian main power grid](https://uio-no.maps.arcgis.com/apps/mapviewer/index.html?webmap=8e4906551c3346249cfd443ca70507cd)

[Municipality level energy consumption](https://uio-no.maps.arcgis.com/apps/mapviewer/index.html?webmap=f1efdace78c741599b34271749afaf14)

[Norwegian population distribution](https://uio-no.maps.arcgis.com/apps/mapviewer/index.html?webmap=3a5917deab76451e944936d75404234c)

Below is the screen shot of one of our interactive maps on ArcGIS Online:

![My Image](ScreenshotInteractiveMaps.png)
