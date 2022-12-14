# Intro to Internet-of-Things networks

With increased use of connected devices such as sensors, switches and actuators - in settings such as Buildings, Cities, Farms and Industries; it is crucial to have reliable network connectivity that ensures stable transmission of data. 

Initially there was a need to be able to read/quantify data from the environment (temperature, pollution, noise etc.) which is where we got the "Things", however with increased usage and need for faster actionable data we got to the phase of those devices comunicating through the internet, leading to "Internet of Things" (IoT). 
Common cases where IoT devices are implemented include: Building management, Asset tracking, Smart Agriculture/farming, Smart Cities etc. 

Until now, typically devices relied on connecting through Wi-Fi networks, Bluetooth or Cellular networks, though they all have their costs and limitations, namely adequate network coverage, power consumption and cost of operation. However not all environments where we want to place sensors have proper internet coverage, or it is not efficient to cover it. Naturally there came a need for a more efficient network by which these numerous devices could operate in a wide area.

As a result, a new network standard was created that is suitable for such purposes, namely as the name itself suggests LoRa stands for 'Long Range'. 

# LoRa

LoRa is a transmission standard between distributed devices and distributed gateways. It is ideal for low power sensors distributed everywhere, with a long operating range. There are two different approaches for the network: a commercial and a community approach. The community approach is based on privately built and operated gateways and in infrastructure which transfers the messages from the gateway to your applications.

![LoRa Diagram 2](https://github.com/sepse/LoRa/blob/main/Graphics/lora2.jpg)

Overall, Wide area in this network standard allow for greater coverage so devices can reliably be placed everywhere and transfer data (vs Wi-Fi, Bluetooth, cellular etc.)

## Pro's
A single LoRaWAN gateway can support thousands of sensor devices in a range of up to 10km (though clear line a sight yields to better data transfer, and increased range). And as the technology is very battery efficient, devices can last up to 5 years, because they transmit very little data from sensor readings in shorter timeframes. 

Free band - becuase the LoRa network utilized a low frequency band, you do not need to apply for a license from regulators nor pay a fee to use it.

## Con's
Nevertheless there is a compromise as well, low power consumption and wide area of coverage allows for very limited data transfer, so network bandwidth is very limited.
The range of the network is directly affected by line-of-sight, less obstructions in between gateways and sensors increase the reliability of data transfer. Careful consideration needs to be given to the placement of the gateway, especially in cities where buildings may obstruct signal. As a rule of thumb, higher placement of antenna as well as open areas are more adequate for a healthier network.

## Network Ecosystem

With the increased use of connected devices, and multiple device manufacturers, the standard was created to allow interoperability and ensure that all devices can communicate across the entire IoT ecosystem. Global collaborative Internet of Things ecosystem was created that creates networks, devices and solutions using LoRa - The Things Network (TTN), open network to build your IoT application.

The Things Network consists of an inclusive and open community of people, companies, governments and universities who are learning, experimenting and building with TTN to realize LoRaWAN solutions.


![LoRa Diagram](https://github.com/sepse/LoRa/blob/main/Graphics/lora1.jpg)


# The case for LoRa in the IoT ecosystem

Considering the benefits of implementing a Wide-Area-Network using LoRa, it seems as a very viable solution for creating solutions where a multitude of devices can communicate to the internet without the hassle of finding or purchasing dedicated network service. Bearing in mind that with just a single gateway one can service thousands of devices, an ideal use case would be in a municipal environment where environmental sensors could generate data for phenomena such as pollution, traffic, streetlight control and other municipal resource management. 

Having numerous sources of data from the sensor network leads to better resource management, and raises awareness about different phenomena (pollution, traffic, security) that can potentially lead to better accountability from local stakeholders.

While such networks are being implemented globaly at a large scale from both commercial service providers as well as the community versions, they serve different goals. Community version (Research institutes, NGO's, Universities) relies on the power of non-commercial stakeholders to implement solutions and gather data for phenomena they are interested in, whereas the commercial version ultimately serves a business goal and is not open to the general public.

Either way, the technology seems to be maturing with a variety of sensor modules out in the market, and with increased standardization between device manufacturers; it seems feasible to ultizie such technology that can serve multiple stakeholders (Commercial, Residential, Municipal, Insitutional), and pave the way to digitalization using modern sensors for use in Buildings, Neighborhoods, Cities and Agriculture. 


