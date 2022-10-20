# Internet-of-Things

With increased use of connected devices such as sensors, switches and actuators - in settings such as Buildings, Cities, Farms and Industries, it is crucial to have reliable network connectivity that ensures stable transmission of data. Initially there was a need to be able to read/quantify data from the environment (temperature, pollution, noise etc.) which is where we got the "Things", however with increased usage and need for faster actionable data we got to the phase of those devices comunicating through the internet, leading to "Internet of Things" (IoT). 
Common cases where IoT devices are implemented include: Building management, Asset tracking, Smart Agriculture/farming, Smart Cities etc. 

Until now, typically devices relied on connecting through Wi-Fi networks, Bluetooth or Cellular networks, though they all have their costs and limitations, namely adequate network coverage, power consumption and cost of operation. However not all environments where we want to place sensors have proper internet coverage, or it is not efficient to cover it. Naturally there came a need for a more efficient network by which these numerous devices could operate in a wide are.

As a result, a new network standard was created that is suitable for such purposes, namely as the name itself suggests LoRa stands for 'Long Range'. 

# LoRa

LoRa is a transmission standard between distributed devices and distributed gateways. It is ideal for low power sensors distributed everywhere, with a long operating range. There are two different approaches for the network: a commercial and a community approach. The community approach is based on privately built and operated gateways and in infrastructure which transfers the messages from the gateway to your applications.

![LoRa Diagram 2](https://github.com/sepse/LoRa/blob/main/Graphics/lora2.jpg)

## Pro's
A single LoRaWAN gateway can support thousands of sensor devices in a range of up to 10km (though clear line a sight yields to better data transfer, and increased range). And as the technology is very battery efficient, devices can last up to 5 years, because they transmit very little data from sensor readings in shorter timeframes. 

Free band - becuase the LoRa network utilized a low frequency band, you do not need to apply for a license from regulators nor pay a fee to use it.

## Con's
Nevertheless there is a compromise as well, low power consumption and wide area of coverage allows for very limited data transfer, so network bandwidth is very limited. 


Overall, Wide area in this network standard allow for greater coverage so devices can reliably be placed everywhere and transfer data (vs Wi-Fi, Bluetooth, cellular etc.)

## Network Ecosystem

![LoRa Diagram](https://github.com/sepse/LoRa/blob/main/Graphics/lora1.jpg)
