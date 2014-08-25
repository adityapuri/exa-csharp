# Problems EXA

## Participate, Learn, Solve and Be Part of [Exzeo](http://exzeosoftware.com)

##### Looking for dynamic, aspiring and self motivated developer to be part of Exzeo Team

##### We have some exiting problems for all you interesting people out there to tease your brain !!!

Any one of the below problems can be chosen to participate. Developers can write a simple Console Application
to showcase the solutions

#### BeatIT
***

~~~ csharp

public interface IContract
{
    void Func1();
    void Func2();
}

/// <remarks>
/// Class is implementing Contarct "IContract"
/// This class represent the concrete implementation of one the client C1
/// requirement  
/// </remarks>
public class ConcreteImplementation1 : IContract
{

    public void Func1()
   {
      //..... Do something......
   }

    public void Func2()
   {
      //..... Do something......
   }
}

/// <remarks>
/// Class is implementing Contarct "IContract"
/// This class represent the concrete implementation of one the client C2
/// requirement  
/// </remarks>
public class ConcreteImplementation2 : IContract
{

    public void Func1()
   {
      //..... Do something......
   }

    public void Func2()
   {
      //..... Do something......
   }
}

~~~

Please carefully read above code where a real life problem has been described. In above scenario, a Contract has been followed by two of the Client and both Contract has something to achieve. Now after some time out of 2 client, one of the client want to have one more addition within his Contract.

How from you code you will facilitate "Client 2" request to add "Func3" without affecting "Client 1"?

#### TrackME
***

![alt text](http://www.gliffy.com/go/publish/image/4690202/M.png "Stations")

Please look at the image carefully which describe scenario as follows:

1. All the stations
2. Distance between station has been mentioned in the Image itself
3. There N vehicles which can be treated as Client. Each client would be initialized as follows:
	1. *C(i, s, d)* where "*C*" is client as vehicle, "*i*" is Initial Station, "*s*" is speed of vehicle and "*d*" is direction(from starting station -> to next station)
	2. *i<>d* where Initial station should not be same 
	3. When destination is reached, Vehicle is considered to be Parked
4. All clients would be initialized and will send signal to Server at constant duration say after every 1km
5. Server will be having information and should show the status of client as follows:
	1. Status of particular client as Moving or Parked
	2. Status of Station as which as all client is near to particular station(Optional for Solution)
	
For simplicity:
1. Speed can be considered as constant of all client 
2. It can be considered that all client are travelling in same direction

All participant should write Clients and Server and showcase this scenario. A simple Console Application as Server and Client can created.

You can use third party libraries too for your solution.

#### WIN-WIN
***


#### Catch Tweet if you can
***


#### So what you have to do once you have your inspiring and excellent solution with you. 

1. Fork the repository from your GitHub account. 
2. Push the code related to solution into Forked repository. You can also let us know through email:adityap@exzeo.com once you are done with your solution. You can let us know that feedback should be published on Github or you can let us know your email address where we can send your feedback that will be private to you.


#### We will get back to you once your solution is verified. 
