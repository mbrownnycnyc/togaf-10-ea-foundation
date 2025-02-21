This course teaches the Togo Standard.

The Togo standard is a best practice framework for enterprise architecture.

But what is enterprise architecture?

Let's look at the terms enterprise and architecture separately.

According to the Togus standard, an enterprise is any collection of organizations that have common

goals.

The term enterprise in the context of enterprise architecture can be applied to either an entire enterprise

encompassing all of its business activities and capabilities, information and technology that make

up the entire infrastructure and governance of the enterprise.

However, the term enterprise can also be applied to only one or more specific areas of interest within

the enterprise.

And enterprise may comprise multiple enterprises.

Just think of a holding company that owns several companies.

The term enterprise may also include partners, suppliers, customers and internal business units.

In all cases, the architecture crosses multiple systems and multiple functional groups within the enterprise.

The Togus standard considers the enterprise as a system, and you may develop and maintain several independent

enterprise architectures.

For example, an enterprise can be defined as a whole corporation, but an enterprise can also be defined

as just a division of the corporation.

Therefore, you can either develop one enterprise architecture for the whole corporation or several

independent enterprise architectures for each division of the corporation.

Which path you choose depends on your goals, resources, area of responsibility and many other things.

Okay, but what is an architecture?

The standard uses the definition from the IEEE 42,010.

Architecture is the fundamental concepts or properties of a systems in its environment, embodied in

its elements, relationships, and the principles of its design and evolution.

The Togo standard adds a second point to this definition the structure of components, their interrelationships,

and the principles and guidelines governing their design and evolution over time.

The focus of the tug of standard is therefore on components and interrelationships, as well as on principles

and guidelines governing design and evolution over time.

In conclusion, the heart of the enterprise architecture are the components of an enterprise and the

interrelationships.

In other words, enterprise architecture describes the interaction between business activities and elements

of information technology, for instance applications, data, and technology.

I don't know about you, but for me, definitions are always very abstract.

In the next learning unit we will look at the concept of architecture domains.

In my opinion, architecture domains are a better and more visual way of explaining enterprise architecture.

What does an enterprise architecture look like?

Let's talk about the concept of architecture domains.

Architecture domains divide an enterprise architecture into four subsets.

The business architecture.

The data architecture.

The application architecture and the technology architecture.

The business architecture defines the business strategy, governance, organization and key business

processes.

The data architecture describes the structure of an organization's conceptual, logical and physical

data assets and data management resources.

The application architecture provides a blueprint for the individual applications to to be deployed,

their interactions, and the relationships to the core business processes of the organization and the

technology.

Architecture describes the digital architecture and the logical software and hardware infrastructure

capabilities and standards that are required to support the deployment of business data and application

services.

Those four domains shape the enterprise architecture.

The three domains data architecture, Application Architecture and Technology Architecture are often

referred to as IT architecture.

You can create other specific domains as a combination of these four domains, for instance digital

architecture or a risk and security architecture.

Back to our four domains business, data, application and technology.

These domains should be linked to each other.

Let me give you an example.

In the business architecture, you describe the business processes of an enterprise.

In the data architecture, you describe the data and information you process in these processes, or

in other words, the inputs and outputs of the business processes.

But in a digitalised world, data has to come from somewhere, be processed, stored and transported.

This is where the different applications of an enterprise come into play.

In the application architecture, you describe the applications that support the business processes

and process the required data.

Last but not least, data and applications need a technical infrastructure to run on.

The technology architecture you describe the hardware infrastructure such as servers and networks,

as well as the technical software infrastructure such as operating systems or virtualization software.

As you can see from this example, the four domains are interconnected and provide a holistic representation

of an enterprise.

This slide shows more examples of what you describe in which domain.

Each architecture domain describes different things.

The business architecture describes business capabilities, value streams, organization units, business

processes, information concepts, and so on.

The data architecture describes information objects, data objects, and data management resources.

The application architecture describes applications, the interfaces and functions, and so on, and

the technology architecture describes IT infrastructure, middleware, network elements, technology

platforms, cloud services, runtime environments and much more.

Let us now take a closer look at the practical application.

What does an enterprise architecture look like?

You can describe or visualize each architecture domain by several artifacts.

For instance, the business architecture can be described with a business capability map that defines

what a business does, or the value stream map that visualizes the strategically relevant activities

of an enterprise, or with an organization map that shows the main organizational units, partners and

stakeholder groups, or the enterprise and their working relationships.

The data architecture can be described, for instance, with a data dissemination diagram that shows

how the logical entities are to be physically realized by application components or with a data entity

business function matrix that depicts the relationship between data entities and business functions

within the enterprise, or with an application data matrix that depicts the relationship between applications

and the data entities that are accessed and updated by them.

Let's take a look at the application architecture.

You can visualize the application architecture with an application portfolio catalog, which is a list

of all applications in the enterprise, or with an application communication diagram, which depicts

the communication or interfaces between applications, or with an application organization matrix,

which depicts the relationships between applications and organizational units within the enterprise.

The technology architecture can be described or visualized with a technology portfolio catalog, which

is a list of all the technology in use across the enterprise, including hardware and infrastructure

software, or with a platform decomposition diagram which depicts the technology platform that supports

the operations of the applications or within the environments and location diagram which depicts what

technologies are used at which locations.

Please note these are just examples and there are many more artifacts to describe an enterprise architecture.

I would like to give you another example of enterprise architecture.

Imagine you're an enterprise architect and your manager wants you to support the digitalization project.

For the order to cash process.

The order to cash process is a business process from customer orders to delivery of the goods to receive

of payment.

This example also illustrates the definition of enterprise.

The Togo standard considers the enterprise as a system.

In this case, the system covers the order to cash process.

We create an enterprise architecture to support the solution delivery for this single project.

In the business architecture domain, we define the order to cash process as the first process level

with the following processes order, fulfillment, delivery, invoice, and cash.

You can also create the second process level if you need more details for the project, let's move on

to the data architecture.

In the order process you need the Information Object purchase order.

This includes, for example, the customer data, the items order, the cost of the items, and so on.

In the invoice process, you need the information object invoice.

This includes the bank data, text data and so on.

I will not read out the other components of the data domain.

I think you understand the concept.

And you'll want to support the entire order to cash process with all the required data using a single

enterprise resource planning application that runs on a cloud platform.

Of course, this is a very simplified example, but I hope that you now know the concept of architecture

domains, what an enterprise architecture is and how an enterprise architecture can be visualized.

Now let's talk about architecture states.

An architecture is always a snapshot in time.

The TOGAF standard differentiates five architecture states depending on the point in time, the approval

of stakeholders, and the realization of value.

We start with the baseline architecture.

This is the current state of the architecture, which serves as a reference for all changes.

Let's continue with the target architecture at the bottom right hand corner.

This is a defined future state of the architecture that the stakeholders have approved.

The baseline and the target architecture are the most important states.

They describe where we are today and where we want to be in the future.

There can be one or more transitional states between the baseline and the target architecture.

This so called transition architectures.

A transition architecture is an architecture in the direction of the target architecture, which already

provides benefits.

A transition architecture is mostly used when the transformation to the target architecture without

intermediate steps is risky or not possible for time, financial or strategic reasons.

In other words, you use a transition architecture when an incremental approach is required.

The transition architecture is a fully functional future state that partially realizes targets with

a specific time and target conformance.

Please note you can have one or more transition architectures partially realizing the target architecture.

You can also have a resting architecture, which is a state where the enterprise receives value if all

change activity is suspended.

In my experience, this state plays a subordinate role.

Last but not least, the candidate architecture.

This is a future state that stakeholders have not approved yet, or in other words, an unapproved target

architecture.

Of course, you often have several candidate architectures as options of which the best architecture

then becomes the target architecture instead of the candidate architecture.

You can also use the term architecture alternatives.

Please note that there is always a baseline architecture, but not necessarily a target, transition

candidate or resting architecture.

So much for architecture states.

Let us now turn our attention to the question how to scope an architecture.

It is important to define and limit the scope of an architecture or an architecture project before you

start to develop the architecture.

There are four dimensions that are used to define and limit the scope of an architecture.

The enterprise scope respectively.

The breadth.

The level of detail or so-called depth.

The architectural domains and the time period, you need to know all of them.

So let's go into detail on all four dimensions.

The breadth defines the enterprise scope that is covered by the architecture.

What is the full extent of the enterprise, and what part of that extent will this architecting effort

deal with?

For example, you can narrow the scope of an architecture project by limiting the scope of consideration

to specific organizations, business units, departments, or processes.

The depth determines how detailed the architecture work should be.

So how much architecture is enough to address the problem at hand?

For example, if you want to explain the most important relationships between data, a rough data model

at the class level should be sufficient.

But if you want to design a database, you need a data model at the attribute level.

The third dimension to limit the scope of an architecture project is the architecture domains.

You can define and limit the scope of an architecture or architecture project with four domains business,

data, application and technology.

Ask yourself, do I really need to know the technology stack of the application landscape to achieve

the goals of the architectural project?

If yes, then you need to look at the technology architecture.

If no, then it may be sufficient to just look at the business processes, their supporting applications

and the data they require.

In other words, you only need to consider the three domains business, data, and application.

Last but not least, the time period.

You should clarify what is the time period that needs to be articulated for the architecture vision?

And does that time period make sense to be covered in a detailed architecture description?

And by does it make sense?

I mean, is it doable?

And do you have enough resources?

To sum up, there are many reasons and benefits to define and limit the scope of an architectural activity,

but the scope is mostly limited by people, finance, objectives, stakeholder concerns, and the organizational

authority or the enterprise architecture team.

In a typical enterprise, many architectures will be described in the architecture landscape at any

point in time.

Some will address detail, some will provide a big picture, some will cover the whole enterprise,

and some will cover just the business unit.

To address this complexity, the Togo standard uses the concept of levels.

Architecture levels divide the enterprise architecture landscape into three levels of granularity.

The strategic architecture.

The segment architecture and the capability architecture.

First, the strategic architecture.

A strategic architecture, provides an operational and change framework and allows for direction setting

at an executive level.

The strategic architecture covers a large breadth, meaning it covers the enterprise to the full extent.

The level of detail is low, and the time period that is articulated in the target architecture is long.

In other words, the target architecture is a broader and less detailed architecture that will generally

be valid for longer periods of time, and can provide a vision for the enterprise that stretches further

into the future.

The second level of granularity is the segment architecture.

A segment architecture provides an operational and change framework and supports direction, setting

and development of architecture roadmaps at a program or portfolio level, and has a medium level of

detail, breadth, and valid time period.

The third level of granularity is the capability architecture.

It is the most detailed architecture level, covering a small breadth of the enterprise.

For instance, just one process or department with a limited valid time period.

A capability architecture provides a change framework and development of architecture roadmaps.

Realizing capability increments.

As you can see in the figure, you can have multiple segment architectures that cover different breadth

and time periods, but all three architectures together cover the same area as the strategic architecture,

just at a higher level of detail.

The same applies to capability architectures, several capability architectures with a higher level

of detail, but smaller time horizon and breadth can detail a segment architecture.

That's it for the concepts of architecture levels and how they divide the enterprise architecture landscape

into three levels of granularity.

An enterprise.

Architecture is complex and usually consists of many different architectures.

The different architectures serve different purposes, cover different areas of the company, and have

different levels of detail and time horizons.

You can now cut this big elephant called enterprise architecture into small slices called architecture

partitions.

An architecture partition is a subset of architecture resulting from dividing that architecture to facilitate

its development and management.

In other words, you divide an architecture into several architecture partitions to simplify the development

and management of the enterprise architecture.

Each partition has defined boundaries, and a team that defines, governs and realizes the architectures

within this partition.

If more than one team is expected to work on a single architecture, this can become problematic as

the precise responsibilities of each team are difficult to establish.

For this reason, it is preferable to apply partitioning to the architecture until each architecture

has one owning team.

Please note partitioning model should reflect the operating model of the enterprise.

Therefore, it is impractical to present a definitive partitioning model for the architecture.

But why is an enterprise architecture partitioned, and how does partitioning simplifies the development

of an enterprise architecture?

First benefit architecture.

Partitions support conflict management.

Organizational unit architectures may conflict with one another.

Conflicts can be eliminated with clear responsibilities for each partition.

Second, benefit architecture partitions allow the parallelization of work.

Different teams need to work on different elements of architecture at the same time, and partitions

allow for specific groups of architects to own and develop specific elements of the architecture.

Third benefit architecture partitions improve the reuse of architectures.

Effective architecture reuse requires modular architecture segments that can be taken and incorporated

into broader architectures and solutions.

Last but not least, architecture.

Partitioning divides inner architecture into subsets to reduce complexity and ensure effective governance

and simplify the development and management of architecture.

Another important concept for architectural work is the architectural abstraction or architectural abstraction

levels.

It is an architectural technique for dividing a problem area into smaller problem areas that are easier

to model, and therefore easier to solve.

Abstraction levels are layered, moving from high level models to more detailed one.

Architecture effort can be divided into four distinct abstraction levels that cross the business, data,

application, and technology domains to answer fundamental questions about an architecture.

The Y level, or contextual level Y is the architecture needed.

The what level or the conceptual level?

What functionality and other requirements need to be met by the architecture?

The how level or the logical level?

How do we structure the functionality and the with what level or the physical level?

With what assets?

Shall we implement the structure?

The contextual abstraction level is focused on understanding the environment in which an enterprise

operates and the context in which architecture work is planned and executed.

It answers why an enterprise undertakes architecture work, what is the scope of the work and the motivation

in terms of goals, drivers and objectives?

The conceptual abstraction is centered on decomposing the requirements to understand the problem and

what is needed to address the problem, without unduly focusing on how the architecture will be realized.

It answers what is necessary to realize the requirements, and is usually modeled using service models

that represent the desired behavior.

The conceptual abstraction level can also be referred to as either service abstraction or behavior abstraction.

The logical abstraction level is focused on identifying the kinds of business data, applications,

and technology components needed to achieve the services identified in the conceptual level.

It is about identifying how an architecture can be organized and structured in an implementation independent

fashion.

Last but not least, the physical abstraction.

This abstraction level manages the allocation and implementation of physical components to meet the

identified logical components.

It is about determining with what physical components the logical level components can be realized.

There will be potentially be many ways to use physical components to realize logical components based

on principles and other grouping criteria, providing different physical solution alternatives.

Please do not mix up the architecture abstraction levels with the levels of the architecture landscape.

The three levels of the architecture landscape are strategic architecture, segment architecture and

capability architecture.

The levels of architecture landscape divide the architecture landscape into three levels of granularity

based on the three dimensions level of detail, breadth and time.

In contrast, the for architecture abstraction levels are contextual abstraction, conceptual abstraction,

logical abstraction, and physical abstraction.

The abstraction level describe the enterprise architecture from different perspectives, but how are

the two concepts level of architecture landscape and architecture abstraction levels related?

You can describe each level of architecture landscape with one or more architectures on a certain abstraction

level.

For example, you can describe a capability architecture with an architecture on a logical abstraction

level and with an architecture on a physical abstraction level.

As a result, you would then have two architecture descriptions of a very detailed capability architecture,

an implementation independent logical architecture, and a physical architecture that describes the

implementation.

That brings us to another important concept of the Torgoff standard building blocks.

A building block, also abbreviated with the two letters B.B., is a package of functionality defined

to meet the business needs across an organization.

Generally, a building block is recognizable as a thing by domain experts and has a type that corresponds

to your enterprise metamodel, for instance actor, business service, application or data entity.

A building block can be defined at various levels of detail, depending on the objective of the enterprise

architecture and the architecture development stage.

For instance, at an early stage, a building block can simply consist of a name or an outline description.

Later on, a building block may be decomposed into multiple supporting building blocks and may be accompanied

by a full specification.

In most cases, a building block leads to improvements in legacy system integration, interoperability,

and flexibility in the creation of new applications.

There is no general set of blocks.

Your organization must decide what arrangement of building blocks works best.

A good building block meets several criteria.

The blog considers implementation and usage and evolves to exploit technology and standards.

It is reusable and replaceable and well specified.

It may be assembled from other building blocks or be a subassembly of other building blocks.

A good building block may interoperate with other interdependent building blocks based on a published

and stable interface.

And lastly, a good building block has defined boundaries and specification which are loosely coupled

to its implementation.

A building block represents a potentially reusable component that can be combined with other building

blocks to deliver architectures and solutions.

The TOGAF standard distinguishes between architecture building blocks, the ABS, and solution building

blocks the SBS.

If a building block delivers an architecture, it is called an architecture building block.

An architecture building block is an architectural component that describes the required capability.

It is logical and supplier independent.

An example of an architecture building block could be the building block.

Video conferencing services.

The AB Video Conferencing Services describes the ability for individuals or groups to communicate and

collaborate in real time via audio and video over the internet.

Architecture.

Building blocks shape the specification of solution building blocks, in turn solution building blocks,

or the so-called SBS deliver solutions.

A solution building block represent components that will be used to implement the required capability.

A solution building block suitable for the architecture building block.

Video conferencing services could, for example, be described with specific software solutions such

as WebEx, zoom or teams, including the required servers and network design, and so on.

Let's summarize the topic of architecture and solution building blocks.

Architecture.

Building blocks describe a required capability, a logical components and supplier independent.

They shape the specification of the solution building blocks.

Solution building blocks are implementation specific physical solution components and implement the

architecture building blocks or that describe the capability.

All right, students, we have already talked a lot about enterprise architecture and about certain

concepts of the TOGAF standard.

However, we have not yet dealt with the TOGAF standard itself.

What is the talk of standard?

Well, the Toga standard is an enterprise architecture framework to develop any kind of architecture

in any context.

It is a best practice framework developed through the collaborative efforts of the community.

The Togo's standard can be used for a range of use cases, for instance to support agile enterprises

or to support the digital transformation.

Basically, it describes a standard cycle of change used to plan, develop, implement governance change

and sustain an architecture.

And describe the building blocks and an enterprise used to deliver business services and information

systems.

The TOGAF standard is suitable for enterprise architecture.

It enables organizations to operate in an efficient and effective way, using a proven and recognized

set of best practices to address business and technology trends.

The Togar standard adds value and enables organizations to build workable and economic solutions.

It also standardizes and de-risks the architecture development.

Using the TOGAF standard results in an enterprise architecture that is consistent, reflects the needs

of the stakeholders, employs best practice, and considers current and future needs of the business.

The TOGAF standard is a generic framework that can and should be tailored to meet the specific needs

of an organization, and can and should be integrated with other frameworks.

This means that on the one hand, you can adopt elements or deliverables from other frameworks and use

them with the TOGAF standard.

And on the other hand, you can also integrate methods, deliverables, or other elements from the TOGAF

standard and integrate them into other frameworks.

If you want to adopt the Togo's standard in your organization, there are usually other frameworks already

in place.

For instance ITIL for IT Service Management, Cobit for governance, and Prince for project management.

You should make sure that these frameworks synergize with the TOGAF standard.

Or in other words, if you adopt the TOGAF standard, you need to look at which parts of the TOGAF standard

and which parts of other frameworks you use and how these elements interact with each other.

Therefore, the Togo's standard should be tailored and integrated into the processes and organization

structures.

But in the end, the TOGAF standard may also be used as a standalone framework.

Let's have a look at the structure of the toga.

Standard.

The toga standard comprises the toga fundamental content and a collection of toga series guides, which

provide the practical guidance in the application of the toga standard.

Let's start with the fundamental content.

The fundamental content is covered by six documents.

It covers the core framework content of the Toga standard.

The first document deals with the introduction and core concepts.

The next three documents all deal with the architecture development method known as the ADM.

The ADM is the heart of the TOGAF standard.

Therefore, three different documents were dedicated to the ADM.

The Document Architecture Development Method describes the ADM as an iterative approach for developing

and managing the life cycle of an enterprise architecture.

The document Adme techniques contains a collection of techniques available for use in applying the TOGAF

approach and the TOGAF ADM.

And the document applying the ADM contains guidelines for adapting the TOC of ADM to address the specific

style of architecture required in a practical context.

Last but not least, the document Enterprise Architecture Capability and Governance.

This document discusses the organization, processes, skills, roles, and responsibilities required

to establish and operate an architecture function within an enterprise and describes an enterprise architecture

governance framework.

Besides the core framework content covered by the six documents explained above, the standard provides

guidance to address specific concerns and use cases through the TOGAF series guides.

The TOGAF series guides are designed to support more specific needs from practitioners who need further

explanation or more detail than that provided in the core content.

Please note all documents of the Togo Standard are free standing but closely linked, regardless of

whether the documents are part of the fundamental content or part of the theories guides.

To put it in a nutshell, the Togo Standard contains guidelines, techniques and advice to create and

maintain an effective enterprise architecture and to deliver change through new solution architectures.

As the architecture development method is so important.

This slide shows an overview of the most important documents on the architecture development method.

The individual guidelines and techniques are described separately so that they can be referenced from

the relevant points in the ADM as necessary.

There are three Toga fundamental content documents on the ADM with the names architecture, Development

method, ADM techniques and applying the ADM.

Furthermore, there is a talk of series guide called A Practitioner's Approach to developing Enterprise

Architecture following the Toga of ADM.

In this series guides, you will find guidance on how to use and adapt the ADM for specific needs.

And last but not least, you can find more white papers and guides classified and referenced in the

TOGAF library.

What is the Hogarth Library?

The Hogarth Library is a portfolio of additional guidance material for the practical application of

the Hogarth Standard.

It accompanies the Toga standard and offers a broad portfolio of guidance material to support the practical

application of the Hogarth approach.

Take a look at the figure on the left.

In the Talgarth Library you will find guidelines, templates, patterns and other reference material,

for instance pocket guides, white papers or reference architectures.

You can leverage the provided content to accelerate the creation of new architectures.

The TOGAF library is part of the open Group library and maintained under the governance of the open

Group Architecture Forum.

Only organizations can become a member of the open Group.

Membership is available to supplier companies and user customer companies, academic and research institutions

and governance agencies, and is subject to annual license fees.

All right, students, so much for the introduction to the Togar standard.