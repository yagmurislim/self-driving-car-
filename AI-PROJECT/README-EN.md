Kahramanmaraş Sütçü İmam Üniversitesi
Mühendislik ve Mimarlik Fakiltesi
Bilgisayar Mühendisliği

dr. öğr üyesi Hasan Badem (danışman)

Twana Ahmed Khudhur
Elif İlhan
İslim Yağmur

Kahramanmaraş - 2021

SELF DRIVING CAR

To run this code,run main.py with python 3.7.
But you have to install these modules NEAT, pygame, numpy and scipy
I have written this code on pycharm IDE



ABOUT THE PROJECT

This is a neural network, its task is to train oneself and learn how to drive a car on a randomly generated road, avoid collisions with road boundaries and trains to go as fast as possible.
But how can he do this?
Very quickly, a neural network, " neural" as named and -1 with the first one connected by a connection weight between the nodes community.
These neurons are arranged in layers, the first of which is called the input layer and the last is called the output layer.
And each can take a value between 0 and 1.
Of the 9 input neurons, 8 represent the car's sensors that detect the distance from the road boundaries in a given direction.
It has a value of 1 if the wall is touching the car, it drops to 0 if the sensor is out of range.
The ninth neuron is the speed of the car, ranging from 0 to its maximum speed.
These nodes can be connected to neurons in the hidden layers or output layers, and the information carried through the link weight is the product of the node value relative to the link weight.
The receiving neurons combine all the input values into one output using a specific function that is then sent forward in the network.
At the end of the chain reaction, the 4 exit nodes have 4 different values that can trigger an action if they go to a certain threshold like 0.5.
These actions tell the car to accelerate, brake, turn left or right.
To create a network that can drive, we need to create the right number of needs in the hidden layers and assign the appropriate weights to the links.
NEAT:
And here we come to the “ NEAT” part , because I used the clean module in python to do this.
NEAT "NeuroEvolution of Augmented Topologies" stands for "NeuroEvolution of Augmented Topologies" and that's how it works.
At the starting line, many simple neural networks are created, each driving its own car.
These networks are randomly generated, so they have absolutely no idea what they are doing.
Since we've already talked about the " neuro " ns , we come to the " Evolution " part here .
Each car is given a point called "fitness".
If they start cruising at supersonic speed and hit the wall, they'll get what they deserve, but if they can stay in the truck longer than their rivals, they'll be in better condition.
And here is where we set the "Augment Topologies" bit: the child will have some properties of the parent, but also new properties that can be a different value in a link, or a new neuron in the hidden layers.
Over the generations, as the new network becomes more complex, its structures {so Topologies} will grow larger to achieve the best possible fit.
As you can imagine, this will take a long time: If you don't want to wait for hours to see a few moves on the screen without crashing, by the way, you can tweak the concept of any racing video game. tunes giving them a lower maximum speed and a tighter return radios .
Pretty soon they'll learn to keep their feet on the gas and never brake, just turn left or right.
Again, like any noop or any racing video game ever
If you have nothing better to do instead, you can make the road narrower or introduce new features such as bikes, intersection, traffic lights, and the greeting nut. so they have no morals and they like to cheat.

