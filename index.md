---
layout: default
---

![Branching](https://user-images.githubusercontent.com/5705572/81245654-2c2d5680-8fdb-11ea-9974-f3cc6857f7c5.png)

# Introduction

Today's modern applications are producing too large volumes of data to be stored, processed, or transferred efficiently. Data reduction is becoming an indispensable technique in many domains because it can offer a great capability to reduce the data size by one or even two orders of magnitude, significantly saving the memory/storage space, mitigating the I/O burden, reducing communication time, and improving the energy/power efficiency in various parallel and distributed environments, such as high-performance computing (HPC), cloud computing, edge computing, and Internet-of-Things (IoT). An HPC system, for instance, is expected to have a computational capability of <img src="https://render.githubusercontent.com/render/math?math=10^{18}"> floating-point operations per second, and large-scale HPC scientific applications may generate vast volumes of data (several orders of magnitude larger than the available storage space) for post-anlaysis.  Moreover, runtime memory footprint and communication could be non-negligible bottlenecks of current HPC systems.

Tackling the big data reduction research requires expertise from computer science, mathematics, and application domains to study the problem holistically, and develop solutions and harden software tools that can be used by production applications. Specifically, the big-data computing community needs to understand a clear yet complex relationship between application design, data analysis and reduction methods, programming models, system software, hardware, and other elements of a next-generation large-scale computing infrastructure, especially given constraints on applicability, fidelity, performance portability, and energy efficiency. New data reduction techniques also need to be explored and developed continuously to suit emerging applications and diverse use cases.

There are at least three significant research topics that the community is striving to answer: (1) whether several orders of magnitude of data reduction is possible for extreme-scale sciences; (2) understanding the trade-off between the performance and accuracy of data reduction; and (3) solutions to effectively reduce data size while preserving the information inside the big datasets. 

The goal of this workshop is to provide a focused venue for researchers in all aspects of data reduction in all related communities to present their research results, exchange ideas, identify new research directions, and foster new collaborations within the community.

<em>Please note this year’s IEEE BigData conference and IWBDR workshop will be held **virtually**. Proceedings of the workshop will be published as planned. We will provide more details about how to attend this workshop virtually soon.</em>

# Submissions

### Topics of Interest

The focus areas for this workshop include, but are not limited to:

- Data reduction techniques for big data issues in _high-performance computing (HPC)_, _cloud computing_, _Internet-of-Things (IoT)_, _edge computing_, _machine learning and deep learning_, and other big data areas:
  - Lossy and lossless compression methods
  - Approximate computation methods
  - Compressive/compressed sensing methods
  - Tensor decomposition methods
  - Data deduplication methods
  - Domain-specific methods, e.g., structured/unstructured meshes, particles, tensors
  - Accuracy-guarantee data reduction methods
  - Optimal design of data reduction methods
- Metrics and infrastructures to evaluate reduction methods and assess fidelity of reduced data
- Benchmark applications and datasets for big data reduction 
- Data analysis and visualization techniques leveraging reduced data
- Characterizing the impact of data reduction techniques on applications
- Hardware-software co-design of data reduction
- Trade-offs between accuracy and performance on emerging computing hardware and platforms
- Software, tools, and programming models for managing reduced data
- Runtime systems and supports for data reduction
- Data reduction challenges and solutions in observational and experimental environments

### Proceedings

All papers accepted for this workshop will be published in the Workshop Proceedings of IEEE Big Data Conference, made available in the IEEE eXplore digital library.

### Submission Instructions

* Camera-ready version of accepted papers must be compliant with the IEEE Xplore format for publication.
* Submissions must be in PDF format.
* Submissions are required to be within **4 pages** for short paper or **8 pages** for full paper (including references).
* Submissions must be single-spaced, 2-column pages in IEEE Xplore format.
* Submissions are NOT double-blind.
* Only web-based submissions are allowed.
* All submission deadlines are Anywhere on Earth
* Please submit your paper via the submission system.
* Submission link: [Cyberchair submissions website](https://wi-lab.com/cyberchair/2020/bigdata20/scripts/submit.php?subarea=S15&undisplay_detail=1&wh=/cyberchair/2020/bigdata20/scripts/ws_submit.php).

### Important Dates

* Paper Submission: ~~October 23~~ October 25, 2020
* Paper Acceptance Notification: November 9, 2020
* Camera-ready Deadline: November 20, 2020
* Workshop: December 10, 2020

# Organizers

### Program Chairs

* Dingwen Tao, _Washington State University_
* Sheng Di, _Argonne National Laboratory_

### Web Chair

Jiannan Tian, _Washington State University_

### Planning Program Committee

* Allison Baker, _National Center for Atmospheric Research_
* Mehmet Belviranli, _Colorado School of Mines_
* Martin Burtscher, _Texas State University_
* Franck Cappello, _Argonne National Laboratory_
* Jon Calhoun, _Clemson University_
* Jieyang Chen, _Oak Ridge National Laboratory_
* Yimin Chen, _Lawrence Berkeley National Laboratory_
* Soumya Dutta, _Los Alamos National Laboratory_
* Pascal Grosset, _Los Alamos National Laboratory_
* Hanqi Guo, _Argonne National Laboratory_
* Muhammad Asif Khan, _Qatar University_
* Beiyu Lin, _University of Texas Rio Grande Valley_
* Shaomeng Li, _National Center for Atmospheric Research_
* Xin Liang, _Oak Ridge National Laboratory_
* Habib Rehman, _Khalifa University_
* Tao Lu, _Marvell Technology Group_
* Panruo Wu, _University of Houston_
* Wen Xia, _Harbin Institute of Technology, Shenzhen_


# Program Schedule (tenative)

### Thursday, December 10, 2020

- **09:00-09:10**: IWBDR – Welcome and Introduction
- **09:10-09:55**: Keynote Speech "Data Reduction Needs and Future Trends for the US Department of Energy" by Dr. Bill Spotz, *Program Manager, DOE ASCR*
- **09:55-10:20**: SDRBench: Scientific Data Reduction Benchmark for Lossy Compressors
- **10:20-10:45**: Assessing Differences in Large Spatio-temporal Climate Datasets with a New Python package
- **10:45-11:10**: Accelerating Text Mining Using a Domain-Specific Stop Word List
- **11:10-11:35**: LCFI: A Fault Injection Tool for Studying Lossy Compression Error Propagation in HPC Programs
- **11:35-11:50**: A Middleware Approach to Leverage Distributed Data Deduplication Capability on HPC and Cloud Storage Systems (short paper)
- **11:50-12:30**: Lunch Break
- **12:30-12:55**: Interpretable Visualization and Higher-Order Dimension Reduction for ECoG Data
- **12:55-13:20**: Efficient Data Management in Neutron Scattering Data Reduction Workflows at ORNL
- **13:20-13:45**: Topology Preserving Data Reduction for Computing Persistent Homology
- **13:45-14:10**: Combining Spatial and Temporal Properties for Improvements in Data Reduction
- **14:10-14:35**: A Fast, Scalable, Universal Approach For Distributed Data Reductions
- **14:35-14:40**: Closing Remarks

All times above are in Eastern Time.

# Participation

Please register at [IEEE BigData 2020](https://bigdataieee.org/BigData2020/Registration.html) and attend the workshop via [Underline](https://underline.io/events/56/sessions?eventSessionId=1547).
