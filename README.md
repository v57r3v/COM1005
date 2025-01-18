java cCOM1005 Machines and IntelligenceWeeks 10-11 Lab Question SheetRobotics  Layered Control Architectures
Instructions
Complete your copy of the lab question sheet, as instructed below.
Download the completed file as a .docx   file and rename it to ‘layered_control_lab.docx’   before submitting.
Base modelImplement the base layered control model (Elowen), according to the given specifications.Adjust the tumble rate to match the ‘one tumble every 5 seconds’ rule, depending on how quickly the periodic control loop runs on your machine.Perform. a series of trials with Elowen in the phototaxis   world, where you let her run in the environment and record the number of steps it took her to run out of energy. For each run, record how many boosters were consumed and how many tumbles were made.In the event of Elowen falling down on the floor, all the trial data should be discarded, as this indicates a problem with the ‘safety’ layer (which should be further improved).Elowen: Base Data
Run #12345678910
Steps                              
Boosters                              
Tumbles                              Elowen: Statistics
# of tr代 写COM1005 Robotics & Layered Control ArchitecturesMatlab
代做程序编程语言ials
Steps:
Min
Steps:
Max
Steps:
Median
Steps:
Mean
Steps:
St. Dev.10               
Modified modelIn the L4 ‘Tumble’ layer of Elowen’s base model, the tumble frequency is fixed and the tumble angle probability distribution is uniform.Implement, describe and evidence a more complex implementation of this layer, which would increase Elowen’s step count, on average, before she runs out of energy in the given environment.(For example, you can use the tumble frequency as a function of the surrounding brightness; and/or you can introduce a more complex probability distribution for tumble angles).Your final MiRoCODE program should support running both models. You can use the ‘modified’   boolean variable provided in the template as a toggle to select which model to run. Answer individually   and in your own words. Use of GenAI tools is NOT allowed. Answer in no more than 200 words. Be specific and include formulas.    Provide figures, tables and/or screenshots if necessary. You can use the steps   and tumbles   as two useful metrics when comparing the base model to the modified model.            
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
