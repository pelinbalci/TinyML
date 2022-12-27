# TinyML 

Ref: https://learning.edx.org/course/course-v1:HarvardX+TinyML1+3T2020/block-v1:HarvardX+TinyML1+3T2020+type@sequential+block@ebe5e04334814f5eb1f0f9d417324194/block-v1:HarvardX+TinyML1+3T2020+type@vertical+block@03848df5c3dd4e96b92cac8290b903ad

The hardware is made up of 3 fundamental building
blocks: 

- the compute, 
- the memory, 
- the storage.


The compute is the brain.  It's effectively where you do the processing.

The memory is where you temporarily store data.  It's like a short-term memory.

And your storage is your permanent hard disk. When you take the power off, it still remembers your data.


A microprocessor is a much bigger piece of computing engine,
versus a microcontroller, the thing that we were talking
about in the previous video, of which there over 250 billion of them
out in the world.

So you have to buy the microprocessor.  And then you put all the other components together.
That's how you build a traditional desktop, for instance.

Microcontoller is already integrated: the processor, the memory and storage. 

An embedded system is typically designed to perform one task. 


In a laptop you have a base operating system like windows, macos or linux, or in a mobiele device you have android or ios.You can
build your applications on top of os and each app has different capabilities, one can take photo other plays music, another make phone calls...

But in embedded system you don't need an operating system. But building efficient system is critical, there are too much specialization.

!!!

Embedded hardware is limited in performance, power consumption and storage

Embedded software is not portable and flexible as mainstream computing

## ML Compression

- ML Models
- ML Runtimes
- ML Hardware


### ML Models:

- Pruning
    Read more: https://pytorch.org/tutorials/intermediate/pruning_tutorial.html
- Quantization  float -> int
- Knowledge Distillation: summarize the info. 

### ML Runtimes:

For example a mobile phone has less compute power, less memmory and it only focuses on inference. You don't necessarily use TF. 
You need stg less memory. 

TensorFlow is for ML Researcher
TensorFlow Lite is for Application Developer

💛 **Architecture:**

Trained TF Model --> TFLite Converter --> TF Lite Model File (.tflite) --> ios or android 

💛 **Architecture in detail:**

- TF: Train Model
- TFLite:
    - Convert Model
    - Optimize Model
    - Deploy Model at Edge : to IOS, Andorid, Microcontoller or Linux(RaspberryPi).
    - Make Inferences at Edge


💛 💛 💛 

Ref: https://learning.edx.org/course/course-v1:HarvardX+TinyML1+3T2020/block-v1:HarvardX+TinyML1+3T2020+type@sequential+block@ebe5e04334814f5eb1f0f9d417324194/block-v1:HarvardX+TinyML1+3T2020+type@vertical+block@3afc4b314c4b43739c5b4e90351057e0
"The Future of TinyML is Bright

We can conjure up a thousand other products. But to get there, first and foremost, Pete, Laurence, and 
I are most passionate about ensuring that the technological imperative behind them is so compelling that we will all 
be able to build whole new applications that we can’t even imagine today. For all of us, it feels a lot like being a kid 
in the Eighties when the first home computers emerged. None of us had any idea what they would become, and most people 
at the time used them for games or storing address books, but there were so many possibilities. A new world emerged out 
of those burgeoning systems. So we challenge you to invent the future. Come on and embrace the future with us by learning 
all we have to teach you about tinyML!"

💛 💛 💛 

# Responsible AI
Ref: https://learning.edx.org/course/course-v1:HarvardX+TinyML1+3T2020/block-v1:HarvardX+TinyML1+3T2020+type@sequential+block@ebe5e04334814f5eb1f0f9d417324194/block-v1:HarvardX+TinyML1+3T2020+type@vertical+block@ae80f75030c049a1a3be19c3a7bf2215

AI introduces new risks and ethical challenges. 

"We cannot build AI into all these tiny, little devices and scatter them out
everywhere thinking that only positive things are going to come out of it.
That would be rather naive."

AI can:
- change human practices
- influence human decisions
- regulate human behavior

💛 Partnership on AI founded to benefit people and society!


## TinyML in industry

💛
- reduce downtime for repairs
- increase efficiency
- cost effective

💥
- accuracy in false alarms and missed detections?
- explainability?
- effect on workflow?

## TinyML in environment

💛
- more detailed insights
- overcome limitations of human labor
- cost effective

💥
- is data reliable?
- who has access the data?
- can devices be hacked by poachers?

## TinyML in humans

💛
- accessible. hands-free
- intuitive UI - Ux
- fewer buttons

💥
- privacy?
- how to protect data?


## Solution

Human centered AI. Ethics is proactive.

- Design 
- Development
- Deployment






