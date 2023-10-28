# ETLJob_StreamingJob_Workflow

![image](https://github.com/phaniteja5789/ETLJob_StreamingJob_Workflow/assets/36558484/2c3e1909-0103-45d5-a6fe-fa25f485f3df)

This entire workflow has been developed using **AWS Step Functions** with appropriate permissions and roles

Workflow has been divided into 2 parts <br/>
1.) ETL WorkFlow <br/>
2.) Streaming WorkFlow <br/>

Workflow will be identified based on intrinsic step functions (States.MathRandom(StartValue, EndValue))

**Used AWS Services**

**Step Functions, Lambda, KINESIS, SNS, S3, Glue, IAM**

**Used Intrinsic Functions in the Step Function**

**States.Format, States.MathRandom, States.StringToJson, States.JsonToString etc** 

Used InputPath, Parameters for Input Filteration and Transformation of Input from one form to another form <br/>

Used ResultPath, and OutputSelector to filter capture both input and output for the next state. <br/>

**Streaming WorkFlow**

