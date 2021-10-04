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


.SUBCKT sky130_fd_bd_sram__openram_dp_cell_dummy BL0 BR0 BL1 BR1 WL0 WL1 VDD GND
** N=14 EP=6 IP=0 FDC=16
*.SEEDPROM

* Bitcell Core
X1 1 GND GND GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X2 1 WL1 BL1 GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X3 2 GND GND GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X4 2 WL1 BR1 GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X5 3 GND GND GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X6 3 WL0 BL0 GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X7 4 GND GND GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15
X8 4 WL0 BR0 GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.15

* drainOnly NMOS
X9 BL1 GND BL1 GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.08
X10 BR1 GND BR1 GND sky130_fd_pr__special_nfet_latch W=0.21 L=0.08

.ENDS
