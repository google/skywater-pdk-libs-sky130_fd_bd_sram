* Copyright 2020 The SkyWater PDK Authors
*
* Licensed under the Apache License, Version 2.0 (the "License");
* you may not use this file except in compliance with the License.
* You may obtain a copy of the License at
*
*     https://www.apache.org/licenses/LICENSE-2.0
*
* Unless required by applicable law or agreed to in writing, software
* distributed under the License is distributed on an "AS IS" BASIS,
* WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
* See the License for the specific language governing permissions and
* limitations under the License.
*
* SPDX-License-Identifier: Apache-2.0

.SUBCKT sky130_fd_bd_sram__openram_dp_cell BL0 BR0 BL1 BR1 WL0 WL1 VDD GND

X0 Q WL1 BL1 GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1
X4 Q_bar WL1 BR1 GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1

X3 BL0 WL0 Q GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1
X7 BR0 WL0 Q_bar GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1

* Bitcell Core
X1 GND Q_bar Q GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1
X2 GND Q_bar Q GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1
X9 Q Q_bar VDD VDD sky130_fd_pr__special_pfet_pass W=0.14u L=0.15u m=1

X5 GND Q Q_bar GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1
X6 GND Q Q_bar GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1
X8 VDD Q Q_bar VDD sky130_fd_pr__special_pfet_pass W=0.14u L=0.15u m=1

* tap under poly
X10 GND GND BL1 GND sky130_fd_pr__special_nfet_latch w=0.21u l=0.08u m=1
X11 GND GND BR1 GND sky130_fd_pr__special_nfet_latch w=0.21u l=0.08u m=1

* drainOnly PMOS
X12 Q_bar WL1 Q_bar VDD sky130_fd_pr__special_pfet_pass W=0.07u L=0.15u m=1
X13 Q WL0 Q VDD sky130_fd_pr__special_pfet_pass W=0.07u L=0.15u m=1

* drainOnly NMOS
X14 GND GND BL1 GND sky130_fd_pr__special_nfet_latch w=0.21u l=0.08u m=1
X15 GND GND BR1 GND sky130_fd_pr__special_nfet_latch w=0.21u l=0.08u m=1


.ENDS
