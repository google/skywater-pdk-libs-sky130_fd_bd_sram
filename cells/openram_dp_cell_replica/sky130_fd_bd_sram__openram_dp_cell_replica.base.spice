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


.SUBCKT sky130_fd_bd_sram__openram_dp_cell_replica BL0 BR0 BL1 BR1 WL0 WL1 VDD GND
** N=9 EP=8 IP=0 FDC=16
*.SEEDPROM

* Bitcell Core
X0 Q WL1 BL1 GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X1 GND VDD Q GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X2 GND VDD Q GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X3 BL0 WL0 Q GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X4 VDD WL1 BR1 GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X5 GND Q VDD GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X6 GND Q VDD GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X7 BR0 WL0 VDD GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X8 VDD Q VDD VDD sky130_fd_pr__special_pfet_pass W=0.14 L=0.15
X9 Q VDD VDD VDD sky130_fd_pr__special_pfet_pass W=0.14 L=0.15

* drainOnly PMOS
*X10 VDD WL1 VDD VDD sky130_fd_pr__special_pfet_pass L=0.08 W=0.14
*X11 Q WL0 Q VDD sky130_fd_pr__special_pfet_pass L=0.08 W=0.14

* drainOnly NMOS
X12 BL1 GND BL1 GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.08
X14 BR1 GND BR1 GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.08

.ENDS
