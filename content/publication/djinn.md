+++
date = "2015-06-13"
title = "DjiNN and Tonic: DNN as a Service and Its Implications for Future Warehouse Scale Computers"
authors = ["Johann Hauswald", "Yiping Kang", "Michael A. Laurenzano", "Quan Chen", "Cheng Li", "Trevor Mudge", "Ronald G. Dreslinski", "Jason Mars", "Lingjia Tang"]

abstract = "As applications such as Apple Siri, Google Now, Microsoft Cortana, and Amazon Echo continue to gain traction, web-service companies are adopting large deep neural networks (DNN) for machine learning challenges such as image processing, speech recognition, natural language processing, among others. A number of open questions arise as to the design of a server platform specialized for DNN and how modern warehouse scale computers (WSCs) should be outfitted to provide DNN as a service for these applications. In this paper, we present DjiNN, an open infrastructure for DNN as a service in WSCs, and Tonic Suite, a suite of 7 end-to-end applications that span image, speech, and language processing. We use DjiNN to design a high throughput DNN system based on massive GPU server designs and provide insights as to the varying characteristics across applications. After studying the throughput, bandwidth, and power properties of DjiNN and Tonic Suite, we investigate several design points for future WSC architectures. We investigate the total cost of ownership implications of having a WSC with a disaggregated GPU pool versus a WSC composed of homogeneous integrated GPU servers. We improve DNN throughput by over 120x for all but one application (40x for Facial Recognition) on an NVIDIA K40 GPU. On a GPU server composed of 8 NVIDIA K40s, we achieve near-linear scaling (around 1000x throughput improvement) for 3 of the 7 applications. Through our analysis, we also find that GPU-enabled WSCs improve total cost of ownership over CPU-only designs by 4-20x, depending on the composition of the workload."

image = ""
image_preview = ""
math = false
publication = "ISCA 2015 - *the 42nd Annual International Symposium on Computer Architecture*"

url_code = ""
url_dataset = ""
url_pdf = "pdf/djinn-isca2015.pdf"
url_project = ""
url_slides = ""
url_video = ""

selected = false
+++