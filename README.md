Term project: Basic Petri net model for a MIPS simulator
This project implements a basic Petri Net simulator for a simplified MIPS Processor.
The model uses colored tokens (token with values) rather than the default Petri net.
Simulator is expected to generate step-by-step simulation of the Petri net model of the MIPS processor as below.


                                                     DI--
                                                     
                                                          \
                                                         
                                                            \
                                                          
                      |Issue2|----LIB----->|ADDR|---ADB--|Load|-\
                      
                        /                                           \
                      
                     /                                                 \
                     
Ii----> |Decoder|--INB-

                   |  |
                      
                   |   \                                                    \

                    \    \                                                   \
                    
                      \    |Issue1|-----AIB--->|ALU|-----------------REB---->|Write|
                      
                        \                                                     /
                        
                         |Read|<----Xi--------------------------------------/
