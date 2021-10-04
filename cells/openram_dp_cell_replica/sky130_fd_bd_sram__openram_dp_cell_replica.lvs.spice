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

* Ingore first line
.SUBCKT sky130_fd_bd_sram__openram_dp_cell_replica BL0 BR0 BL1 BR1 WL0 WL1 VDD GND

* Bitcell Core
X0 Q WL1 BL1 GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1
X1 GND VDD Q GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1
X2 GND VDD Q GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1
X3 BL0 WL0 Q GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1
X4 VDD WL1 BR1 GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1
X5 GND Q VDD GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1
X6 GND Q VDD GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1
X7 BR0 WL0 VDD GND sky130_fd_pr__special_nfet_latch W=0.21u L=0.15u m=1
X8 VDD Q VDD VDD sky130_fd_pr__special_pfet_pass W=0.14u L=0.15u m=1
X9 Q VDD VDD VDD sky130_fd_pr__special_pfet_pass W=0.14u L=0.15u m=1

* tap under poly
X10 GND GND BL1 GND sky130_fd_pr__special_nfet_latch w=0.21u l=0.08u m=1
X11 GND GND BR1 GND sky130_fd_pr__special_nfet_latch w=0.21u l=0.08u m=1

* drainOnly PMOS
X12 Q WL0 Q VDD sky130_fd_pr__special_pfet_pass w=0.07u l=0.15u m=1
X13 VDD WL1 VDD VDD sky130_fd_pr__special_pfet_pass w=0.07u l=0.15u m=1

* drainOnly NMOS
X14 GND GND BL1 GND sky130_fd_pr__special_nfet_latch w=0.21u l=0.08u m=1
X15 GND GND BR1 GND sky130_fd_pr__special_nfet_latch w=0.21u l=0.08u m=1

.ENDS
