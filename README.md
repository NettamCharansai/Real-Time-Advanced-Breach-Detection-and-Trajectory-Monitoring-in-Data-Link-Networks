# \# Real-Time Breach Detection and Trajectory Monitoring in Data Link Networks

# 

# > \*\*🔒 Strict Confidentiality Notice:\*\* The source code for this project is highly confidential and proprietary. This repository serves as a research overview and technical showcase. For inquiries or further details, please contact the contributors directly via email.

# 

# \## 📌 Project Leadership \& Contributions

# \* \*\*Contributors:\*\* Charan Sai Nettam, Bobbili Sai Jayanth 

# \* \*\*Project Manager:\*\* Jagadish Prasad (Senior Scientist- 'F', DRDO-RCI, Hyderabad)

# \* \*\*Contact:\*\* charansainettam@gmail.com | jayiit12993@gmail.com

# 

# \---

# 

# \## 🎯 Overview

# This project developed a real-time system for breach detection and trajectory monitoring within data link networks compliant with the \*\*MIL-STD 1553\*\* standard (the backbone of modern defence and aerospace communication). 

# 

# Traditional trajectory monitoring methods struggle with real-time data loss, sensor faults, and non-linear patterns in high-stakes environments. To solve this, we engineered a system utilizing advanced Machine Learning and Quantum Computing models to predict object trajectories, identify communication breaches, and reconstruct missing data using cubic spline interpolation.

# 

# \## ⚙️ Core Architecture \& Tech Stack

# \* \*\*Quantum Machine Learning:\*\* PennyLane Quantum (QNN)

# \* \*\*Classical Machine Learning:\*\* Support Vector Regression (SVR), Random Forests (RF) (Scikit-learn, MATLAB)

# \* \*\*Data Link Protocol:\*\* MIL-STD 1553

# \* \*\*Interface \& Visualization:\*\* React.js, Python, MATLAB (3D Trajectory Visualization)

# \* \*\*Data Processing:\*\* Cubic Spline Interpolation for real-time missing value imputation.

# 

# \## 📊 Model Performance \& Benchmarks

# 

# We evaluated three primary models for handling high-throughput defence sensor data. While SVR and RF provided strong baseline accuracy, the \*\*Quantum Neural Network (QNN)\*\* demonstrated superior real-time processing capabilities.

# 

# | Model | Precision | Recall | Accuracy | Key Advantage |

# |---|---|---|---|---|

# | \*\*Support Vector Regression (SVR)\*\* | 0.94 | 0.93 | 96.5% | Excels in stable, noise-free, non-linear environments. |

# | \*\*Random Forest (RF)\*\* | 0.95 | 0.90 | 95.8% | Highly robust against missing temporal gaps and large datasets. |

# | \*\*Quantum Neural Network (QNN)\*\* | 0.97 | 0.94 | 97.2% | \*\*Best Overall:\*\* Leverages quantum states for parallel processing, ideal for real-time GUI applications. |

# 

# \## 🚀 Key Deliverables \& Impact

# 1\. \*\*Real-Time GUI Integration:\*\* Built a high-frequency, real-time graphical interface using React.js and Python to visualize live dynamic object paths and alert operators to trajectory deviations.

# 2\. \*\*Data Reconstruction:\*\* Engineered a pipeline that successfully imputes missing temporal gaps in sensor data on the fly, preventing model collapse during transmission errors.

# 3\. \*\*Quantum Acceleration:\*\* Proved the viability of QNNs for real-time path guidance and breach detection in aerospace applications, significantly reducing computation time compared to classical deterministic models.

