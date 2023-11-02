# Facade Pattern
The Facade Design Pattern is a structural design pattern that provides a unified interface to a set of interfaces in a subsystem. It defines a higher-level interface that makes the subsystem easier to use. In simple words, the Facade Design Pattern is used to hide the complexities of a system and provides an easy-to-use interface to the client using which the client can access the system.


# Simplified Hotel Management System

The HotelApp needs to manage various hotel services for guest check-in and check-out. These services include valet parking for vehicles, room cleaning, and handling luggage carts. However, the HotelApp aims to interact with these services through a simplified, single interface provided by the FrontDesk. The FrontDesk class should delegate the client's requests to the appropriate service classes (Valet, HouseKeeping, Cart) while abstracting the service details from the client.

# Class Definitions
- HotelService (Interface): Defines the common interface for all hotel services. <br>
- Valet: A service class implementing the HotelService interface, responsible for vehicle valet parking and pick-up. It includes the pickUpVehicle(plateNumber) method. <br>
- HouseKeeping: A service class implementing the HotelService interface, responsible for room cleaning. It includes the cleanRoom(roomNumber) method. <br>
- Cart: A service class implementing the HotelService interface, responsible for handling luggage cart requests. It includes the requestCart(numberOfCarts) method. <br>
- FrontDesk: The facade class that coordinates interactions between the client (HotelApp) and the individual hotel services. <br>
- HotelApp: The client class that uses the FrontDesk facade to access and utilize hotel services seamlessly. <br>

# Implementation of Adapter Pattern

<p align="center">
  <img src="https://github.com/SG-Hangaan/FacadePattern/assets/127215110/f60d6897-ac62-4d1a-99d5-29391035d2c1"/>
</p>

<p align="center">
  <img src="https://github.com/SG-Hangaan/FacadePattern/assets/127215110/3aa44898-cc81-45fd-a260-799da2b90b9e"/>
</p>

# UML Class Diagram


