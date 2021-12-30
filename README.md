![LinkDisable in loopback mode](Documents/Screenshot_LinkDisable.png)

*******************************************************************************
Use functions instead of ROM tables for gray <-> binary encoding and some generalization of FIFO size<br/>
Fixed hang when LinkDisable is used (link should now restart properly and flush FIFOs)<br/>
Added loopback for testing purposes<br/>
Config moved to top file as constants<br/>
Stats as vector instead of array<br/>
Translated the PDF doc to english (kind of)<br/>
Note that current SpW config is for (as noted in the PDF)<br/>
50MHz system clock<br/>
100MHz Tx clock<br/>
167MHz Rx clock<br/>
2021/12/29 Walter<br/>
*******************************************************************************
Open-source SpaceWire CODEC IP Core              Ver 1.21           2014/06/18<br/>
*******************************************************************************
-------------------------------------------------------------------------------
|   File Name                                   | Version |        Date        |
-------------------------------------------------------------------------------
SpaceWireCODECIP.vhdl                            Ver 1.20<br/>
SpaceWireCODECIPFIFO9x64.vhdl                    Ver 1.20<br/>
SpaceWireCODECIPLinkInterface.vhdl               Ver 1.20<br/>
SpaceWireCODECIPPackage.vhdl                     Ver 1.20<br/>
SpaceWireCODECIPReceiverSynchronize.vhdl         Ver 1.21           2014/06/18<br/>
SpaceWireCODECIPStateMachine.vhdl                Ver 1.20<br/>
SpaceWireCODECIPStatisticalInformationCount.vhdl Ver 1.20<br/>
SpaceWireCODECIPSynchronizeOnePulse.vhdl         Ver 1.20<br/>
SpaceWireCODECIPTimeCodeControl.vhdl             Ver 1.20<br/>
SpaceWireCODECIPTimer.vhdl                       Ver 1.20<br/>
SpaceWireCODECIPTransmitter.vhdl                 Ver 1.20<br/>
*******************************************************************************



