# Atlas Thing Framework

The success of Internet of Things (IoT) technology is about expanding ways for people to interact, engage and program their smart homes or workplaces. Such success cannot be achieved through simple connections between smart things, but will depend on how these things are prepared to support this promising vision. We also argue that for the realization of innovative IoT scenarios, application development environments should not be based only on available services but also on relationships that logically and functionally tie these services opportunistically. Social networking concepts converged into a new paradigm named Social IoT (SIoT). SIoT evolves a social network for smart things through a set of social interactions for new smart space programmability. 

</br>
IoT currently lacks a uniform way of describing the thing which makes it difficult for the thing to integrate itself with the rest of the ecosystem, or for the user or programmer to manage, configure and develop applications for such heterogeneous things. At the same time, the current state of SIoT and smart space programmability present limited social interactions and relationships that restricts proliferation of new applications. Our Atlas thing framework is composed of the following components:


> - We present the [IoT Device Description Language (IoT-DDL)](https://github.com/AtlasFramework/IoT-DDL) as a XML-based machine- and human-readable descriptive language and configuration schema, which seeks to achieve thing seamless integration and homogenization through describing a thing in IoT in terms of inner components, identity, capabilities, resources, attachments and services.


> - A lightweight architecture named [Atlas Thing Architecture](https://github.com/AtlasFramework/Atlas-Thing-Architecture) is designed and implemented to utilize the specifications of IoT-DDL. The architecture provides new capabilities a thing must have to be easily configured and managed. The architecture enables the thing to self-discover itself and announce its presence, services and capabilities to other participants in the smart space to discover and build new social relationships. Along with the provisioning and management capabilities, the architecture supports both thing-to-thing and thing-to-cloud communication through the support of a set of protocols. 


> - The [Inter-thing relationships programming framework]() utilizes the architecture as well as the IoT-DDL specifications to build a distributed programming ecosystem for the social IoT. The framework broadens the social IoT thing-level relationships and utilizes a set of concrete service-level relationships to program a much wider class of meaningful IoT applications.


<p align="center">
  <img src="https://github.com/AtlasFramework/Atlas-Thing-Architecture/blob/master/Resources/AtlasThingArchitecture.jpg" width="700" height="550" title="The Architecture">
</p>
