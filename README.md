# Student Cluster Competition

# Advisors
* Greg Byrd-- Primary Team Advisor  Email: gbyrd@ncsu.edu
* John Ravi-- Team Advisor Email: jjravi@ncsu.edu
* Frank Mueller-- Team Advisor Email: fmuelle@ncsu.edu
* Michela Becchi-- Team Advisor Email: mbecchi@ncsu.edu
* Berra Kara-- Team Advisor  Email: bnkara@ncsu.edu

# Team
* Michael Kersting-- Team Member Email: mwkersti@ncsu.edu
* Quinn Dibble-- Team Member Email: qdibble@ncsu.edu


SC20 Conference Website can be found [here](https://sc20.supercomputing.org/)


## Textbooks
These are some of the books I have in mind so far, but might add/remove some of these as needed. They are all avaiable through NCSU Library

1. [CUDA by Example-- An Introduction to General-Purpose GPU Programming by Jason Sanders and Edward Kandrot](https://www.amazon.com/CUDA-Example-Introduction-General-Purpose-Programming-ebook/dp/B003VYBOSE/ref=sr_1_1?ie=UTF8&qid=1549751175&sr=8-1&keywords=CUDA+by+Example--+An+Introduction+to+General-Purpose+GPU+Programming+by+Jason+Sanders+and+Edward+Kandrot)
2. [Bioinformatics-- High Performace Parallel Computer Architectures by Bertil Schdmit](https://www.amazon.com/Bioinformatics-Performance-Parallel-Architectures-Multi-Core-ebook/dp/B005GGLE7Q/ref=sr_1_1?s=home-garden&ie=UTF8&qid=1549751144&sr=8-1&keywords=Bioinformatics+High+Performance+Parallel+Computer+Architectures)
3. [Machine Learning with TensorFlow by Nishant Shukla with Kenneth Fricklas](https://www.amazon.com/Machine-Learning-TensorFlow-Nishant-Shukla/dp/1617293873/ref=sr_1_fkmr0_1?ie=UTF8&qid=1549751259&sr=8-1-fkmr0&keywords=Machine+Learning+with+TensorFlow+by+Nishant+Shukla+with+Kenneth+Fricklas)
4. [Designing and Building Parallel Programs](https://www.mcs.anl.gov/~itf/dbpp/)

## HPC Resources on campus
| Server                   | Software |
|--------------------------|----------|
| ssh grendel.ece.ncsu.edu |          |
| ssh hydra.ece.ncsu.edu   | cuda     |

## Team Logistics



## Tentative Schedule for this competition
Date | Topic | Reading  | Online Lectures | Workshops/Meetings | Notes |
---- | :---: | --- | --- | --- | ---|
Week of 2/11 | Intro to Parallel Programming. | [Intro Reading](https://github.ncsu.edu/bnkara/Student-Cluster-Competition/blob/master/Readings/CUDA_ch1.pdf). [Chapters: Overview and Concepts and Terminology](https://computing.llnl.gov/tutorials/parallel_comp/#Abstract) . |  [Intro to Parallel Programming](https://classroom.udacity.com/courses/cs344). [Fundamentals of Parallelism on Intel Architecture](https://www.coursera.org/learn/parallelism-ia/home/welcome) NOTE: see this [page](https://projects.ncsu.edu/hpc/Documents/Compilers.php) for Intel compilers for Henry2. | Dr. Byrd meets with Trudi Brown. Berra metts with John Ravi from Dr. Becchi's research group. Team meets. | Programming in C/C++ in Linux and Linux shell knowledge is required before starting the online courses. Some basic knowledge of computer architecture is assumed. [Install the free CUDA toolkit on your machine](https://developer.nvidia.com/how-to-cuda-c-cpp) . Finish two weeks. It would be nice if you guys can also finish week 3.|
Week of 2/18 | Intro to CUDA. Parallel Programming in CUDA. | [Getting Started with CUDA Reading](https://github.ncsu.edu/bnkara/Student-Cluster-Competition/blob/master/Readings/CUDA_ch2.pdf) . [Introduction to CUDA](https://github.ncsu.edu/bnkara/Student-Cluster-Competition/blob/master/Readings/CUDA_ch3.pdf) . [High Performance Computing- Tools and Applications](https://github.ncsu.edu/bnkara/Student-Cluster-Competition/blob/master/Vectorization/High%20Performance%20Computing-%20Tools%20and%20Applications.pdf) . [Vectorization with Intel C++ compilers](https://github.ncsu.edu/bnkara/Student-Cluster-Competition/blob/master/Vectorization/(Auto)%20Vectorization%20tutorial.pdf) .  | Continue working on weeks 3 and 4 on the Intel course. We will try to finish week 5 either this week or next week.  | Team meets. Team is finalized!! | [Create an Overlef account to get started on the proposal](https://www.overleaf.com/) . HW: [Vectorization Lab](https://github.ncsu.edu/bnkara/Student-Cluster-Competition/blob/master/vector_lab.pdf) .  |
Week of 2/25 | Practice? | [More notes on MPI](https://computing.llnl.gov/tutorials/mpi/#Abstract) . [Notes on OpenMP from LLNL](https://computing.llnl.gov/tutorials/openMP/) . [Performance Analysis Tools](https://computing.llnl.gov/tutorials/performance_tools/). |   | Michael presents Python . Quinn presentes Ubuntu. | |
Week of 3/4 | CSC 548 Material | [Intro](https://github.ncsu.edu/bnkara/Student-Cluster-Competition/blob/master/Readings/csc548/lec1.ppt) . Message Passing |   | Berra and Tri | |
Week of 3/11 |  | |   | Spring break, so no meeting. However, finish the assigments and readings | |
Week of 3/18 |  | |   |  | |
Week of 3/25 |  | |   |  | |
Week of 4/1 |  | |   |  | |
Week of 4/8 |  | |   |  | |
Week of 4/15 |  | |   |  | |
Week of 4/22 |  | |   |  | |
Week of 4/29 |  | |   |  | |
Week of 5/6 |  | |   |  | |
Week of 5/13 |  | |   |  | |
Week of 5/20 |  | |   |  | |
Week of 5/27 |  | |   |  | |
Week of 6/3 |  | |   |  | |
Week of 6/10 |  | |   |  | |
Week of 6/17 | |[CUDA COURSE](https://courses.nvidia.com/courses/course-v1:DLI+C-AC-01+V1/info) [Linkedin](https://docs.google.com/document/d/1lWitPKM4fwQM1J_P53D1wH6Ly4PvkINO7PYmsloVSZc/edit)|   |  | |
Week of 6/24 |  | |   |[See meeting minute](https://docs.google.com/document/d/1TuleSoKE5MpZIBMvYg6ShJAdlxDtR8A7lTCg5mCnris/edit)   | |
Week of 7/1 | Application Released  | [VPIC](https://github.com/lanl/vpic), [SST](http://sst-simulator.org/SSTPages/SSTMainDocumentation/), [Reproductive Challenge](https://github.com/js1019/NormalModes) |   |[See meeting minute](https://docs.google.com/document/d/1jJHWBygodzy-4Zx1eyyLYv9zlmYQhIeoArvYA7A0mhE/edit)   |Assigning Team |
Week of 7/28 |  | |   |  | |

Week of 8/10 |  | |   |  | |

Week of 8/17 |  | |   |  | |

Week of 8/24 |  | |   |  | |

Week of 8/31 |  | |   |  | |

Week of 9/7  |  | |   |  | |

Week of 9/14 |  | |   |  | |

Week of 9/21 |  | |   |  | |

Week of 9/28 |  | |   |  | |

Week of 10/05 |  | |   |  | |

Week of 10/12 |  | |   |  | |

Week of 10/19 |  | |   |  | |

Week of 10/26 |  | |   |  | |

Week of 11/02 |  | |   |  | |

Week of 11/09 |  | |   |  | |

Week of 11/16 | CONFERENCE WEEK | |   |  | |
