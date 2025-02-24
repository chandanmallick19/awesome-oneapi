# awesome-oneapi
An Awesome list of oneAPI projects

A curated list of awesome oneAPI and SYCL projects for solutions across industry and community. Inspired by [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning).

## What is oneAPI?

oneAPI is an open, cross-industry, standards-based, unified,
multiarchitecture, multi-vendor programming model that delivers a common
developer experience across accelerator architectures – for faster
application performance, more productivity, and greater innovation. See,
https://oneapi.io/ for more information.

## Table of Contents

1. [AI - Computer Vision](#AI-\--Computer-Vision)
2. [AI - Data Science](#AI-\--Data-Science)
3. [AI - Machine Learning](#AI-\--Machine-Learning)
4. [AI - Natural Language Processing](#AI-\--Natural-Language-Processing)
5. [AI - Frameworks and Toolkits](#AI-\--Frameworks-and-Toolkits)
6. [Autonomous Systems](#Autonomous-Systems)
7. [Data Visualization and Rendering](#Data-Visualization-and-Rendering)
8. [Energy](#Energy)
9. [Gaming](#Gaming)
10. [Manufacturing](#Manufacturing) 
11. [Mathematics and Science](#Mathematics-and-Science)
12. [Tools & Development](#Tools-and-Development)
13. [Tutorials](#Tutorials)


### AI - Computer Vision

* [BMW-IntelOpenVINO-Detection-Inference-API](https://github.com/BMW-InnovationLab/BMW-IntelOpenVINO-Detection-Inference-API) - This is a repository for an object detection inference API using OpenVINO, supporting both Windows and Linux operating systems
* [Certiface Anti-Spoofing](https://github.com/cabelo/oneapi-antispoofing) - Certiface AntiSpoofing use oneAPI for fast decode video for perform liveness detection with inference. The system is capable of spotting fake faces and performing anti-face spoofing in face recognition systems.
* [LidarObjectDetection-PointPillars](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics/End-to-end-Workloads/LidarObjectDetection-PointPillars) (C++ based, requires AI toolkit and OpenVINO). demonstrates how to perform 3D object detection and classification using input data (point cloud) from a LIDAR sensor.
* [deepEye](https://github.com/nullbyte91/deepEye) - The Deepeye project proposes an advanced assist system for visually impaired people that would provide navigation at a low cost. It aims to use computer vision and Opencv along with the Oak-D module and Depth AI for improved perception of the surroundings.
* [diffusers](https://github.com/pykeio/diffusers) - Pyke Diffusers is a modular Rust library for pretrained diffusion model inference to generate images using ONNX Runtime as a backend for accelerated generation on both CPUs and GPUs, including features like low memory usage and quantization. It offers an interactive stable diffusion demo and instructions on how to install and use the tool.
* [Fast_Human_Pose_Estimation_Pytorch](https://github.com/yuanyuanli85/Fast_Human_Pose_Estimation_Pytorch) - This is an unofficial implementation for the paper "Fast Human Pose Estimation". The code mainly comes from the PyTorch implementation for Stacked Hourglass Network.
* [gocv](https://github.com/hybridgroup/gocv) - The gocv package is a set of Go bindings for the OpenCV 4 computer vision library that supports the latest releases of Go and OpenCV v4.7.0 on Linux, macOS, and Windows.
* [RapidOCR](https://github.com/RapidAI/RapidOCR) - This is the README for RapidOCR, a project that provides OCR tools and models for detecting text in images.
* [smart-retail-analytics](https://github.com/intel-iot-devkit/smart-retail-analytics) - The retail analytics application uses video or camera resources to monitor activity and keep track of inventory.
* [Stable Diffusion](https://github.com/Stability-AI/stablediffusion) - This repository contains Stable Diffusion models trained from scratch and will be continuously updated with new checkpoints. 
* [stable_diffusion_arc](https://github.com/rahulunair/stable_diffusion_arc) - The project guide provides instructions on how to set up and run the stable diffusion inference model on Intel Arc GPUs.
* [stable-diffusion-webui-arc-directml](https://github.com/Aloereed/stable-diffusion-webui-arc-directml) - The project involves a web UI for stable diffusion on Intel ARC with DirectML.
* [stable_diffusion.openvino](https://github.com/bes-dev/stable_diffusion.openvino) - This GitHub project provides an implementation of text-to-image generation using stable diffusion on Intel CPU or GPU. It requires Python 3.9.0 and is compatible with OpenVINO.
* [yolov5_export_cpu](https://github.com/SamSamhuns/yolov5_export_cpu) - The project provides documentation on exporting YOLOv5 models for fast CPU inference using Intel's OpenVINO framework

### AI - Data Science

* [Boosting epistasis detection on Intel CPU+GPU systems](https://github.com/hiperbio/cross-dpc-episdet) - This work focuses on exploring the architecture of Intel CPUs and Integrated Graphics and their heterogeneous computing potential to boost performance and energy-efficiency of epistasis detection. This will be achieved making use of OpenCL Data Parallel C++ and OpenMP programming models.
* [Drift Detection for Edge IoT Applications](https://github.com/blackout-ai/Face_Aging_Concept_Drift) - This concept drift project is run on video and image datasets such that we can calculate an overall precision and standard error. The concept drift detection technique finds True positives and False negatives using real and virtual drift detection. 
* [HIAS TassAI Facial Recognition Agent](https://github.com/AIIAL/HIAS-TassAI-Facial-Recognition-Agent) - Security is an important issue for hospitals and medical centers to consider. Today's Facial Recognition can provide ways of automating security in the medical industry reducing staffing costs and making medical facilities safer for both patients and staff.

### AI - Machine Learning

* [DQRM](https://anonymous.4open.science/r/Deep_Quantized_Recommendation_Model_DQRM-6B4D) - Deep Quantized Recommendation Model (DQRM) is a recommendation framework that is small, powerful in inference, and efficient to train.
* [Performance and Portability Evaluation of the K-Means Algorithm on SYCL with CPU-GPU architectures](https://github.com/artecs-group/k-means) - This work uses the k-means algorithm to asses the performance portability of one of the most advanced implementations of the literature He-Vialle over different programming models (DPC++ CUDA OpenMP) and multi-vendor CPU-GPU architectures.

### AI - Natural Language Processing

* [Census](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics/End-to-end-Workloads/Census)  (Python based) Use Intel® Distribution of Modin to ingest and process U.S. census data from 1970 to 2010 in order to build a ridge regression based model to find the relation between education and the total income earned in the US.
* [ChatGPTCLIBot](https://github.com/LagPixelLOL/ChatGPTCLIBot) - The chatgpt cli bot allows the user to run GPT models such as GPT 3.5 and GPT 4, and switch between them using the config.json file.
* [CTranslate2](https://github.com/OpenNMT/CTranslate2) - CTranslate2 is a C and Python library that optimizes inference with transformer models, supporting models trained in various frameworks. It implements various performance optimization techniques such as weights quantization, layers fusion, batch reordering, and more for benchmarks of transformer models on CPU and GPU.
* [fastRAG](https://github.com/IntelLabs/fastRAG) - Build and explore efficient retrieval-augmented generative models and applications. It's main goal is to make retrieval augmented generation as efficient as possible through the use of state-of-the-art and efficient retrieval and generative models.
* [Gavin AI](https://github.com/Gavin-Development/GavinTraining) - Gavin AI is a project created by Scot_Survivor (Joshua Shiells) ShmarvDogg which aims to have English human like conversations through the use of AI and ML. Gavin works on the Transformer architecture however Performer FNet architectures are being investigated for better scaling.
* [hachi](https://github.com/ramanlabs-in/hachi) - Hachi is a locally hosted web app that enables natural language search for videos and images, using an AI-based machine learning model powered by OpenAI CLIP.
* [Language Identification](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics/End-to-end-Workloads/LanguageIdentification) (Python based) Trains a model to perform language identification using the Hugging Face Speechbrain library and CommonVoice dataset, and optimized with IPEX and INC.
* [whisper-ctranslate2](https://github.com/Softcatala/whisper-ctranslate2) - Whisper ctranslate2 is a command-line client based on ctranslate2, compatible with original OpenAI client.

### AI - Frameworks and Toolkits

* [AI Personal Identifiable Information Data Protection](https://github.com/oneapi-src/ai-data-protection) - Provides anonyimzation functions, which include methods for masking, hashing and encrypting/decrypting the PII data in large datasets. Can be used to protect the privacy and security of individuals in a dataset.
* [AI Structured Data Generation](https://github.com/oneapi-src/ai-structured-data-generation) - Generate structured synthetic data for training and inferencing.
* [AI based transcribing](https://github.com/oneapi-src/ai-transcribe) - A reference solution showing how to use speech to text conversion to convert audio session tapes into digital notes in a psychologist's office.
* [BMW-Anonymization-API](https://github.com/BMW-InnovationLab/BMW-Anonymization-API) - The BMW Anonymization API is a privacy tool designed to obfuscate sensitive information in images and videos to preserve individual anonymity. Its features include agnostic localization techniques, modular sensitive information training, scalable anonymization techniques, and compatibility with deep learning models
* [Credit Card Fraud Detection](https://github.com/oneapi-src/credit-card-fraud-detection) - Uses Intel AI Analytics Toolkit and scikit-learn to train a AI algorithm to detect credit card fraud.
* [Customer Chatbot](https://github.com/oneapi-src/customer-chatbot) - a pytorch based conversational AI chatbot for customer care.
* [Customer Churn Prediction](https://github.com/oneapi-src/customer-churn-prediction) - Using historical customer churn data along with service details, a machine learning model built to predict whether the customer is going to churn. Reducing churn is key in the telecommunications industry to attract new customers and avoid contract terminations.
* [Customer Segmentation for Online Retailers](https://github.com/oneapi-src/customer-segmentation) - Demonstrates how machine learning can aid in building a deeper understanding of a businesses clientele by segmenting customers into clusters that can be used to implement personalized and targeted campaign.
* [Data Streaming Anomaly Detection](https://github.com/oneapi-src/data-streaming-anomaly-detection) - help detect anomalies using tensorflow and oneAPI to build a deep learning model that can detect anomalies in data collected from a IOT device to monitor equipment condition and prevent any issue from being cascaded.
* [deeplearning4j](https://github.com/deeplearning4j/deeplearning4j) - The Eclipse DeepLearning4J ecosystem supports all the needs for JVM-based deep learning applications with various libraries
* [deeplearning4j-examples](https://github.com/deeplearning4j/deeplearning4j-examples) - The Eclipse Deeplearning4j (DL4J) ecosystem is a set of projects that supports all the needs of a JVM-based deep learning application.
*  [DeepRec](https://github.com/DeepRec-AI/DeepRec) - DeepRec is a recommendation deep learning framework based on TensorFlow, which has been developed since 2016 and supports core businesses such as Taobao search recommendation and advertising.
* [Demand Forecasting](https://github.com/oneapi-src/demand-forecasting) - Builds and trains an AI model using deep learning to train and utiliez a CNN-LSTM time series model that predicts the next days demand every item based on 130 days worth of sales data.
* [Digital Twin for Design Exploration](https://github.com/oneapi-src/digital-twin) - A model that can be used to test digital replicas of real world products or devices for faults.
* [Disease Prediction](https://github.com/oneapi-src/disease-prediction) - Demonstrates using a deep learning based NLP pipeline to train a document classifier that takes in notes from patient's symptoms and predicts the diagnoses among a set of known diseases.
* [dlstreamer](https://github.com/dlstreamer/dlstreamer) - The Intel Deep Learning Streamer is an open source streaming media analytics framework based on the GStreamer multimedia framework. It is optimized for performance and functional interoperability between GStreamer plugins built on various backend libraries, with support for over 70 pre-trained models for various use cases.
* [Documentation Automation](https://github.com/oneapi-src/document-automation) - based on the Tensorflow BERT transfer learning NER Model, build a deep learning model to predict the named entity tags for a given sentence.
* [Drone Navigation Inspection](https://github.com/oneapi-src/drone-navigation-inspection) - Find safe drone landing zone without damaging property or injuring people using oneAPI and TensorFlow.
* [Engineering Design Optimizations](https://github.com/oneapi-src/engineering-design-optimization) - Train a model to create new bicycle designs with unique frames and handles, and generalize rare novelties to a broad set of designs, competely automatic and without requiring human intervention.
* [flashlight](https://github.com/flashlight/flashlight) - Flashlight is a machine learning library written in C and created by Facebook AI Research. It features internal APIs for tensor computation, high performance defaults using just-in-time kernel compilation, and scalability
* [Historical Assets Document Processing \(OCR\)](https://github.com/oneapi-src/historical-assets-document-process) - Allows you to process large amounts of structured, semi-structured and unstructured content in documents. Through the use of image processing, analysis, text region detection and text extraction using OCR - the results can then be stored and can be put into a database.
* [Image Data Generation](https://github.com/oneapi-src/image-data-generation) - An AI-enabled image generator that aids in generating accurate image and image segmentation datasets where availability of such datasets are limited.
* [intel-extension-for-tensorflow](https://github.com/intel/intel-extension-for-tensorflow) - Intel Extension for TensorFlow is a plugin based on TensorFlow PluggableDevice, which aims to bring devices such as Intel XPU, GPU, and CPU into TensorFlow.
* [intel-extension-for-transformers](https://github.com/intel/intel-extension-for-transformers) - Intel Extension for Transformers is a toolkit designed to efficiently accelerate transformer-based models on Intel platforms, optimized for 4th gen Intel Xeon Scalable Processor (codename Sapphire Rapids).
* [intel-extension-for-pytorch](https://github.com/intel/intel-extension-for-pytorch) - Intel Extension for PyTorch provides features optimizations for an extra performance boost on Intel hardware including CPUs and Discrete GPUs and offers easy GPU acceleration for Intel Discrete GPUs with PyTorch.
* [Invoice To Cash Automation](https://github.com/oneapi-src/invoice-to-cash-automation) - AI toolkit to extract information from claim documents to categorize the claims. Helps develop models to accelerate the resolution of accounts receivable claims for trade promotion deductions.
* [Intelligent Indexing](https://github.com/oneapi-src/intelligent-indexing) - A reference kit to build an AI-based Natural Language Processing solution for classifying documents.
* [KernelAbstractions.jl](https://github.com/JuliaGPU/KernelAbstractions.jl) - KernelAbstractions (KA) is a package that enables you to write GPU-like kernels targetting different execution backends.  
* [Loan Default Risk Prediction](https://github.com/oneapi-src/loan-default-risk-prediction) - Train and utilize an AI model using XGBoost to predict the probability of a loan default from client characteristics and the type of loan obligation.
* [Medical Imaging Diagnostics](https://github.com/oneapi-src/medical-imaging-diagnostics) - Using machine learning and deep learning, train an AI algorithm that identifies images that warrant further attention to classify abnormalities.
* [models](https://github.com/onnx/models) - The ONNX Model Zoo is a collection of pre-trained, state-of-the-art machine learning models in the ONNX format. These models are contributed by community members and accompanied by Jupyter notebooks for model training and running inference with the trained model.
* [Network Intrusion Detection](https://github.com/oneapi-src/network-intrusion-detection) - A pattern based network intrusion system using oneAPI and machine learning.
* [neural-compressor](https://github.com/intel/neural-compressor) - Intel Neural Compressor is an open-source Python library for applying popular model compression techniques, such as pruning, quantization, sparsity, and distillation, on all mainstream deep learning frameworks and Intel extensions.
* [nnfusion](https://github.com/microsoft/nnfusion) - A flexible and efficient deep neural network (DNN) compiler that generates high-performance executable from a DNN model description.
* [optimum](https://github.com/huggingface/optimum) - Optimum is an extension of Transformers and Diffusers that provides optimization tools for efficiency to train and run machine learning models on targeted hardware, while also being easy to use.
* [optimum-intel](https://github.com/huggingface/optimum-intel) - Optimum Intel is an interface between the Transformers and Diffusers libraries and Intel's different tools and libraries that help accelerate end-to-end pipelines on Intel architectures.
* [Order to Delivery Time Forecasting](https://github.com/oneapi-src/order-to-delivery-time-forecasting) - A machine learning based predictive model that provides delivery time forecasting for e-commerce platform.
* [pipeline-server](https://github.com/dlstreamer/pipeline-server) - Intel Deep Learning Streamer (DL Streamer) is a Python package and microservice that supports the deployment of optimized media analytics pipelines. It includes customizable media analytics containers, APIs to monitor pipelines, no-code pipeline definitions, and deep learning model integration with openvino.
* [Power Line Fault Detection](https://github.com/oneapi-src/powerline-fault-detection) - Process and analyze signals from a 3-phase power supply system used in power lines to predict whether or not a signal has a partial discharge using SciPy and NumPy calculations.
* [Predictive Asset Maintenance](https://github.com/oneapi-src/predictive-asset-health-analytics) - Shows an alternative method of using oneAPI AI Analytics Toolkit over the stock version of the same package like XGBoost.
* [Product Recommedation](https://github.com/oneapi-src/product-recommendations) - A reference kit that demonstrates one way where AI can be used to build a recommendation system for an e-commerce business using scikit-learn and oneAPI.
* [Purchase Prediction](https://github.com/oneapi-src/purchase-prediction) - A oneAPI based reference AI model that uses machine learning to predict purchases of customers.
* [pycaret](https://github.com/pycaret/pycaret) - PyCaret is an open-source, low-code machine learning library in Python that automates the machine learning workflow. It is an end-to-end machine learning and model management tool that replaces hundreds of lines of code with a few lines to make experiments exponentially fast and efficient.
* [pynufft](https://github.com/jyhmiinlin/pynufft) - The pynufft library is a Python package for non-uniform fast Fourier transform, based on a min-max interpolator, with experimental support for CuPy, PyTorch, and TensorFlow Eager mode
* [scikit-learn-intelex](https://github.com/intel/scikit-learn-intelex) - Intel r Extension for scikit learn is a free AI accelerator that can accelerate existing scikit learn code without the need to change the existing code. It offers patching and replacing the stock scikit learn algorithms with their optimized versions provided by the extension, which results in over 10-100x acceleration across a variety of applications.
* [shumai](https://github.com/facebookresearch/shumai) - The Shumai project is a differentiable tensor library for TypeScript and JavaScript built with Bun and Flashlight. It provides standard array utilities, gradients, and supported operators.
* [Structural Damage Assessment](https://github.com/oneapi-src/structural-damage-assessment) - A PyTorch-based AI model that works on satellite-captured images to assess the severity of damage in the aftermath of a natural disaster.
* [Synthetic Voice/Audio Generation](https://github.com/oneapi-src/voice-data-generation) - Generate synthetic voices and speeches - can be used in chatbots, virtual assistants, and is applicable in a host of applications. Voice synthesis technology is increasingly used to create more natural sounding virtual assistants.
* [Text Data Generation](https://github.com/oneapi-src/text-data-generation) - Creates synthetic data that is artificially generated. This reference kit uses a pre-trained GPT2 modle provided by hugging face to generate synthetic data applicable to product testing and training machine learning algorithms without running into privacy issues.
* [Traffic Camera Object Detection](https://github.com/oneapi-src/traffic-camera-object-detection) - reference kit demonstrating how to improve traffic using a number of different technology and oneAPI.
* [Vertical Search Engine](https://github.com/oneapi-src/vertical-search-engine) - Demonstrates a possible reference implementation of a deep learning based NLP pipeline for semantic search of an organization's document using a pre-trained model.
* [Visual Process Discovery](https://github.com/oneapi-src/visual-process-discovery) - A reference kit implementing visual process discovery. VPDs can be used to enhance customer experience by providing personalized solutions knowing their needs as they navigate through a company's website.
* [Visual Quality Inspection](https://github.com/oneapi-src/visual-quality-inspection) - Build a computer vision based model for building quality visual inspection based on a dataset from the pharma industry.
* [webnn-native](https://github.com/webmachinelearning/webnn-native)- WebNN Native is an implementation of the Web Neural Network API, providing building blocks, headers, and backends for ML platforms including DirectML, OpenVINO, and XNNPACK.
* [ZenDNN](https://github.com/amd/ZenDNN) - Zen deep neural network library ZendNN is a powerful library for deep learning inference applications on AMD CPUs. It includes APIs for basic neural network building blocks and is optimized for AMD CPUs.

### Autonomous Systems

* [Alice](https://github.com/intel/dffml/tree/alice/entities/alice/) - We are writing a tutorial for an open source project on how we build an AI to work on the open source project as if she were a remote developer. Bit of a self fulfilling prophecy but who doesn't love an infinite loop now and again.

### Data Visualization and Rendering

* [Atrc](https://github.com/AirGuanZ/Atrc) - The ATRC offline rendering lab includes various features such as path tracing, photon mapping, and many material models. It has an optional integrated OIDN and Embree library and an interactive scene editor.
* [Blender](https://github.com/blender) - Blender is the free and open source 3D creation suite. It supports the entirety of the 3D pipeline-modeling, rigging, animation, simulation, rendering, compositing, motion tracking and video editing.
* [Brayns](https://github.com/BlueBrain/Brayns) - Brayns is a large scientific visualization platform based on CPU ray tracing, using an extension plugin architecture. It comes with several pre-made plugins, such as CircuitExplorer and MoleculeExplorer, and requires several dependencies to build
* [ChameleonRT](https://github.com/Twinklebear/ChameleonRT) - ChameleonRT is an example path tracer that runs on multiple ray tracing backends including Embree, SYCL, DXR, Optix, Vulkan, Metal, and Ospray.
* [embree](https://github.com/embree/embree) - Embree is a high performance ray tracing library developed by Intel that targets graphics application developers to improve the performance of photo-realistic rendering applications. It includes various primitive types such as triangles, quads, grids, and curve primitives, and supports dynamic scenes. Embree also offers support for both CPUs and GPUs, while maintaining one code base to improve productivity and eliminate inconsistencies between the two versions of the renderer.
* [fresnel](https://github.com/glotzerlab/fresnel) - Fresnel is a Python library for path tracing that can be used to generate high quality images in real time.
* [f3d](https://github.com/f3d-app/f3d) - F3D is a fast and minimalist 3D viewer that supports multiple file formats and can show animations, supporting thumbnails and many rendering and texturing options including real-time physically based rendering and raytracing.
* [hdospray](https://github.com/ospray/hdospray) - The ospray for hydra is an open-source plugin for Pixar's USD to extend the hydra rendering framework with Intel Ospray. It is highly optimized for Intel CPU architectures ranging from laptops to large-scale distributed HPC systems.
* [ml-hypersim](https://github.com/apple/ml-hypersim) - The HyperSim dataset is a photorealistic synthetic dataset for indoor scene understanding that includes dense per-pixel semantic instance segmentations and complete camera information for every image.
* [oidn](https://github.com/OpenImageDenoise/oidn) - Intel Open Image Denoise is an open-source library for image denoising in ray tracing rendering applications with high quality and performance, thanks to efficient deep learning-based filters that can be trained using the included toolkit and user-provided image datasets.
* [openpgl](https://github.com/OpenPathGuidingLibrary/openpgl) - The Intel Open Path Guiding Library (Open PGL) implements path guiding into a renderer, offering implementations of current state-of-the-art path guiding methods which increase the sampling quality and renderer efficiency.
* [ospray](https://github.com/ospray/ospray) - Ospray is an open source, scalable and portable ray tracing engine designed for high fidelity visualization on Intel architecture CPUs. It allows users to easily build interactive applications using ray-tracing based rendering for both surface and volume-based visualizations.
* [ospray_studio](https://github.com/ospray/ospray_studio) - Ospray Studio is an open-source, interactive visualization and ray tracing application that utilizes Intel Ospray as its core rendering engine. Users can create scene graphs to render complex scenes with high-fidelity or very large scenes requiring supercomputing resources.
* [point-cloud-utils](https://github.com/fwilliams/point-cloud-utils) - Point Cloud Utils (PCU) is an easy-to-use Python library for processing and manipulating 3D point clouds and meshes. It provides several algorithms for generating point samples on meshes, downsampling point clouds, and computing distances between point clouds.
* [redner](https://github.com/BachiLi/redner) - Redner is a differentiable renderer that can compute correct rendering gradients stochastically without approximation. It can simulate photons and produce realistic lighting phenomena, and handle the derivatives of these features correctly.
* [SORT](https://github.com/JiayinCao/SORT) - Sort is a cross platform physically based renderer that can be used as a standalone ray tracing program or as a renderer plugin for Blender.
* [Substrate](https://github.com/seelabutk/substrate) - A toolset to help developers create and deploy cloud-based VaaS services (Visualization as a Service). Deployment targets include any platforms capable of running Docker Swarm, such as Amazon AWS, institutional clusters and even personal servers. Native for Python environment (pip installable).
* [tracer](https://github.com/JoshuaSenouf/tracer) - Tracer is a renderer that uses Embree and USD to produce photorealistic images using path tracing on the CPU, with features like subpixel jitter antialiasing, depth of field, and a variety of integrators.
* [vistle](https://github.com/vistle/vistle) - Vistle is a modular data-parallel visualization system. It requires a C++14 compatible compiler that supports ISO/IEC 14882:2014, alongside compiling requirements of Boost, CMake and MPI. Additionally, it supports Covise, OpenCover, OpenSceneGraph and Qt 5 libraries, and also provides support code, rendering libraries, controlling code for Vistle session and visualization algorithm modules.
* [volppm](https://github.com/yumcyaWiz/volppm) - Volppm is a volumetric progressive photon mapping project that features homogeneous mediums for chromatic absorption and scattering coefficients.
* [yocto-gl](https://github.com/xelatihy/yocto-gl) - Yocto GL is a collection of small C++17 libraries for building physically based graphics algorithms. Each library is split into smaller ones, making code navigation easier.

### Energy

* [A DPC++ Backend for the OCCA Portability Framework](https://github.com/libocca/occa) - OCCA—an open source portable and vendor neutral framework for parallel programming on heterogeneous platforms—is used by mission critical computational science and engineering applications of public and private sector organizations including the U.S. Department of Energy and Shell.

### Gaming

* [NovelRT](https://github.com/novelrt/NovelRT) - NovelRT is a cross-platform game engine for visual novels and 2D games. It is still in the early alpha stage, but currently supports graphics and audio.

### Manufacturing

* [S3_DeformFDM](https://github.com/zhangty019/S3_DeformFDM) - The S3 Slicer is a framework for achieving support-free strength reinforcement and surface quality in multi-axis 3D printing by computing the rotation-driven deformation for the input model.


### Mathematics and Science

* [1D Heat Transfer Simulation](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C%2B%2BSYCL/StructuredGrids/1d_HeatTransfer) - (C++ based, from Intel) This 1D-Heat-Transfer sample is an application that simulates the heat propagation on a one-dimensional isotropic and homogeneous medium. The code sample includes both parallel and serial calculations of heat propagation.
* [3D Wave Simulation](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C%2B%2BSYCL/StructuredGrids/guided_iso3dfd_GPUOptimization) - (C++ based, from Intel) The ISO3DFD sample refers to Three-Dimensional Finite-Difference Wave Propagation in Isotropic Media; it is a three-dimensional stencil to simulate a wave propagating in a 3D isotropic medium. Starts with a simple serial implementation and shows how to use SYCL to offload to the GPU. Then shows how to optimize.
* [ACTS GPU Ramp](https://github.com/acts-project/traccc) - Demonstrator tracking chain on accelerators
* [arpack-ng](https://github.com/opencollab/arpack-ng) - Arpack ng is a collection of Fortran77 subroutines designed to solve large scale eigenvalue problems and is a community project maintained by volunteers.
* [Amber](https://ambermd.org/GetAmber.php) Amber is a high-performance molecular dynamics (MD) code used by thousands of scientists in academia, national labs, and industry for computational drug discovery and related research.
* [ATLAS Charged Particle Seed Finding with DPC++](https://github.com/acts-project/acts) - The ATLAS Experiment is one of the general-purpose particle physics experiments built at the Large Hadron Collider (LHC) at CERN in Geneva. Its goal is to study the behavior of elementary particles at the highest energies ever produced in a laboratory help us better understand universe.
* [Discrete Cosine Transform Imeage Compression](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C%2B%2BSYCL/SpectralMethods/DiscreteCosineTransform) - (C++ based, from Intel) The Discrete Cosine Transform (DCT) sample demonstrates how DCT and Quantizing stages can be implemented to run faster using SYCL* by offloading image processing work to a GPU or other device.
* [Direction Field Visualization with Python](https://github.com/olutosinbanjo/direction_field) - This project demonstrates the visualization of a direction field with Python using the differential equation of a falling object as a case study.  The effectiveness of Heterogeneous Computing is also shown by exploring optimized libraries added functionalities in Intel® Distribution for Python.
* [GinkgoOneAPI](https://github.com/ginkgo-project/ginkgo) - In this project we want to explore the potential of having an Intel OneAPI backend for the Gingko software package: https://ginkgo-project.github.io/
* [GROMACS](https://www.gromacs.org/) A free and open-source software suite for high-performance molecular dynamics and output analysis.
* [repulsive-surfaces](https://github.com/icethrush/repulsive-surfaces) - A numerical framework for optimization of surface geometry while avoiding (self-)collision.
* [GeometricTools](https://github.com/davideberly/GeometricTools) - The Geometric Tools Engine (GTE) is a collection of source code for high-performance computing in mathematics, geometry, graphics, image analysis, and physics, using CPU multithreading and GPU programming.
* [gptoolbox](https://github.com/alecjacobson/gptoolbox) - This is a toolbox of useful MATLAB functions for geometry processing, constrained optimization and image processing. It contains several features such as mesh deformation, mesh parameterization, and discrete differential geometry operators for triangle and tetrahedral meshes.
* [Homogeneous and Heterogeneous Implementations of a tridiagonal solver on Intel® Xeon® E-2176G with oneMKL getrs](https://github.com/olutosinbanjo/oneMKL_getrs.git) - Homogeneous and Heterogeneous implementations of a tridiagonal solver with oneMKL getrs
* [Jacobi Iterative Solver for Multi-GPU](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C%2B%2BSYCL/DenseLinearAlgebra/guided_jacobi_iterative_gpu_optimization) - (C++ based, from Intel) Illustrates how to use the Jacobi Iterative method to solve linear equations. This sample starts with a CPU-oriented application and shows how to use SYCL to offload regions of the code to a GPU. The sample walks through developing an optimization strategy by iteratively optimizing the code and ultimately targetting multi-GPUs if available.
* [LAMMPS](https://github.com/lammps/lammps) - AMMPS is a classical molecular dynamics simulation code designed to run efficiently on parallel computers.  It was developed at Sandia National Laboratories, a US Department of Energy facility, with funding from the DOE.  It is an open-source code, distributed freely under the terms of the GNU Public License (GPL) version 2.
* [mapmap_cpu](https://github.com/dthuerck/mapmap_cpu) - MapMap CPU is a massively parallel generic MRF map solver with minimal input assumptions, capable of solving a large class of MRF problems.
* [MF-LBM](https://github.com/lanl/MF-LBM) - This is a lattice Boltzmann code designed for direct numerical simulation of flow in porous media. It is written in Fortran 90 and optimized for vectorization and parallel programming.
code to SYCL. 
* [Monte Carlo Based Finanical Simulation for Multi-GPU](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C%2B%2BSYCL/MapReduce/guided_MonteCarloMultiGPU_SYCLMigration) - (C++ based, from Intel) Evaluates fair call price for a given set of European options using the Monte Carlo approach. MonteCarlo simulation is one of the most important algorithms in quantitative finance. This sample uses a single CPU Thread to control multiple GPUs. Shows how to migrate CUDA based code to SYCL.
* [mt-kahypar](https://github.com/kahypar/mt-kahypar) - MT-KaHyPar is a multi-threaded algorithm for partitioning graphs and hypergraphs. It aims to minimize an objective function defined on the hyperedges while balancing block sizes and optimizing connectivity. It can partition extremely large graphs and hypergraphs with comparable solution quality to the best sequential graph partitioners while being more than an order of magnitude faster with only ten threads.
* [NAMD](https://www.ks.uiuc.edu/Research/namd/) is a parallel molecular dynamics code designed for high-performance simulation of large biomolecular systems.
* [NWGraph](https://github.com/pnnl/NWGraph) - The Northwest Graph Library (NWGraph) is a high-performance header-only generic C++ graph library based on C++20 concepts and ranges. It includes multiple graph algorithms for well-known graph kernels and supporting data structures.
* [Odd Even Merge and Sorting](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C%2B%2BSYCL/StructuredGrids/1d_HeatTransfer) - (C++ based, from Intel) Demonstrates how to use the odd-even mergesort algorithm (also known as "Batcher's odd–even mergesort") which may benefit whenn working with  batches of short-sized to mid-sized (key, value) array pairs.  Shows how to migrate CUDA based code to SYCL.
* [Optical Flow Method](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C%2B%2BSYCL/StructuredGrids/guided_HSOpticalflow_SYCLMigration) - (C++ based, from Intel) The HSOpticalFlow sample is a computation of per-pixel motion estimation between two consecutive image frames caused by movement of object or camera. Shows how to migrate CUDA based code to SYCL.
* [PyPardisoProject](https://github.com/haasad/PyPardisoProject) - Pypardiso is a Python package for solving large sparse linear systems of equations using the Intel OneAPI Math Kernel Library Pardiso solver. It provides the same functionality as Scipy's spsolve but is faster in many cases.

### Tools and Development

* [ArrayFire - oneAPI Backend](https://github.com/arrayfire/arrayfire) - ArrayFire is a general-purpose tensor library that simplifies the process of software development for the parallel architectures found in CPUs GPUs and other hardware acceleration devices. This project is to develop a oneAPI backend to the library which currently supports CUDA OpenCL and x86.
* [chip-spv](https://github.com/CHIP-SPV/chip-spv) - The "chip spv" project allows for the portability of HIP and CUDA applications to platforms supporting SPIR-V. Currently, it offers support for OpenCL and Level-Zero as low-level runtime alternatives.
* [formulog](https://github.com/HarvardPL/formulog)** - Formulog is a logic programming language that supports Datalog, SMT queries, and first-order functional programming. It requires JRE 11 and a supported SMT solver, such as Z3, Boolector, CVC4, or Yices.
* [HeCBench](https://github.com/zjin-lcf/HeCBench) - The hecbench repository contains a collection of benchmarks for studying performance portability and productivity with various heterogeneous computing languages.The benchmarks are divided into categories like computer vision, bioinformatics, and finance.
* [HPCToolKit](http://hpctoolkit.org/) - HPCToolkit is an open-source performance tool that is in some respects similar to VTune though it also works on Power and ARM architectures. It also works on NVIDIA and AMD GPUs. Our aim is to also use it for performance analysis of Intel GPUs with Intel’s OpenCL to our targets as a prelude to A0
* [Kokkos](https://github.com/kokkos/kokkos) - Kokkos Core implements a programming model in C++ for writing performance portable applications targeting all major HPC platforms. For that purpose it provides abstractions for both parallel execution of code and data management. Kokkos is designed to target complex node architectures with N-level memory hierarchies and multiple types of execution resources. It currently can use CUDA, HIP, SYCL, HPX, OpenMP and C++ threads as backend programming models with several other backends in development.
* [libxsmm](https://github.com/libxsmm/libxsmm) - LIBXSMM is a library for specialized dense and sparse matrix operations as well as for deep learning primitives such as small convolutions. 
* [numba-dpex](https://github.com/IntelPython/numba-dpex) - Numba dpex is an extension for the Numba Python JIT compiler that provides a kernel programming API and an offload feature. It supports devices including Intel CPUs, integrated GPUs, and discrete GPUs.
* [oneapi-containers](https://github.com/intel/oneapi-containers) - The Intel OneAPI Containers simplify programming by delivering the tools to deploy applications and solutions on various architectures. These containers allow developers to set up and distribute environments for profiling and execute applications built with OneAPI toolkits.
* [oneAPI.jl](https://github.com/JuliaGPU/oneAPI.jl) - The oneapi.jl GitHub project provides support for working with the oneapi unified programming model and offers low-level wrappers for the level zero library, kernel programming, and high-level array programming capabilities.
* [Open-source Scientific Applications and Benchmarks](https://github.com/zjin-lcf/oneAPI-DirectProgramming) - This repository contains a collection of data-parallel programs for evaluating oneAPI direct programming. Each program is written with CUDA, SYCL, and OpenMP target offloading. Intel® DPC++ Compatibility Tool (DPCT) can convert a CUDA program to a SYCL program.
* [OpenVisualCloud Dockerfiles](https://github.com/OpenVisualCloud/Dockerfiles) - This repository contains Docker build files for software stacks and services designed for media delivery, media analytics, cloud gaming and graphics, and immersive media.
* [QSVEnc](https://github.com/rigaya/QSVEnc) - QSVenc is a software developed to investigate the performance and image quality of the hw encoder QSV of Intel. It is a command line version that runs independently and a plugin for AviUtl.
* [RcppParallel](https://github.com/RcppCore/RcppParallel) - The rcppparallel project provides high-level functions for parallel programming with Rcpp and supports using Intel TBB for performance on Windows, macOS, and Linux systems. 
* [Scal](https://devmesh.intel.com/projects/scalsale) - New physical scalable benchmark, namely ScalSALE, is based on the well-known SALE scheme. ScalSALE's main goal is to provide a gold-standard benchmark application that can incorporate multi-physical schemes while maintaining scalable and efficient execution times.
* [SYCLomatic](https://github.com/oneapi-src/SYCLomatic) - The SycloMatic project helps developers migrate code to the SYCL heterogeneous programming model. Daily builds are available, but not rigorously tested for production quality control.
* [TAU Performance System](https://github.com/UO-OACISS/tau2) - The TAU Performance System® supports profiling and tracing of programs written using the Intel OneAPI. Intel OneAPI provides two interfaces for programming - OpenCL and DPC++/SYCL for CPUs and GPUs. TAU supports both - the OpenCL profiling interface and Intel Level Zero API to observe performance. 
* [TornadoVM](https://github.com/beehive-lab/TornadoVM) - TornadoVM is an open-source software technology that automatically accelerates Java programs on multi-core CPUs GPUs and FPGAs.
* [toyBrot](https://gitlab.com/VileLasagna/toyBrot) - toyBrot is a raymarching fractal generator that is used both as a  simple benchmarking tool and a study tool for parallelisation. The code is is implemented with over 10 different technologies including Intel TBB ISPC and SYCL (with support for oneAPI)
* [ZFP](https://github.com/LLNL/zfp) - zfp is a compressed format for representing multidimensional floating-point and integer arrays. zfp provides compressed-array classes that support high throughput read and write random access to individual array elements. zfp also supports serial and parallel compression of whole arrays for applications that read and write large data sets to and from disk.

## Tutorials

* [50YearsOfRayTracing](https://github.com/neil3d/50YearsOfRayTracing) - This GitHub project is focused on ray tracing and covers several techniques and models developed from 1968 to 1997, with a focus on physically based rendering.
* [data-parallel-CPP](https://github.com/Apress/data-parallel-CPP) - The Data Parallel C Book Source Samples repository contains code that accompanies the Data Parallel C: Mastering DPC for Programming of Heterogeneous Systems using C++ and SYCL book.
* [efficient-dl-systems](https://github.com/mryab/efficient-dl-systems) - This repository contains materials for the Efficient Deep Learning Systems course taught at the HSE University and Yandex School of Data Analysis.
* [Jurassic](https://github.com/IntelSoftware/Jurassic) - Hunting Dinosaur bones using AI
* [syclacademy](https://github.com/codeplaysoftware/syclacademy) - SYCL Academy, a set of learning materials for SYCL heterogeneous programming

<!-- ## Financial Services -->

