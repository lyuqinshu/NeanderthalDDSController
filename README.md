<a name="readme-top"></a>
<!-- ABOUT THE PROJECT -->
## About The Project

NeanderthalDDSController is designed to control SPECTRUM M4i.96xx-x8 DDS card. The programme generates a timed pattern using the device's internal clock, writes the pattern into the device buffer, waits for an external trigger to excecute the patter, then repeat.

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- GETTING STARTED -->
## Getting Started



### Prerequisites

* A SPECTRUM M4i.96xx-x8 DDS card.
* Software driver provided by SPECTRUM
  

### Installation

1. Install the card driver.

2. Add SpcmDrv64.NET.dll to the dependence.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Operation

1. Build your pattern on GUI. Event time in ms, all frequencies are in MHz, amplitudes between 0 to 1, frequency ramp in MHz/ms and amplitude ramp in 1.0/ms.
2. Click on Start Pattern. It will write the pattern into the hardware buffer and wait for an external trigger to Trg0.
3. Send a trigger pulse to Trg0, the board will output the pattern. The trigger will be re-armed after the pattern length time set in GUI.
4. The process will repeat till you click Stop Pattern.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Update Log

* [v 1.0.0] Feb 10th 2025: Alpha test version.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact
Please contact Qinshu Lyu Github/lyuqinshu if you find any issues or have any suggestions.



<p align="right">(<a href="#readme-top">back to top</a>)</p>






