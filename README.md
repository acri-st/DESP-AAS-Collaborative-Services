# DESP-AAS Collaborative Services

This project contains multiple microservices designed to simulate our production environment.

## Table of Contents
- [🧭 What is the Collaborative Services?](https://github.com/acri-st/DESP-AAS-Collaborative-Services#-what-is-the-collaborative-services)
- [⚙️ Technical description](https://github.com/acri-st/DESP-AAS-Collaborative-Services#%EF%B8%8F-technical-description)
  - [🗺️ Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)
  - [📄 Microservices description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#-microservices-description)
    - [📦 Collaborative UI](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main?tab=readme-ov-file#-what-is-the-collaborative-ui-back-to-architecture)
    - [📦 Asset Management](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-asset-management-back-to-architecture)
    - [📦 Recommendation](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-recommendation-back-to-architecture)
    - [📦 Search](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-search-back-to-architecture)
    - [📦 Discussion](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-discussion-back-to-architecture)
    - [📦 Geo Extractor](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-geo-extractor-back-to-architecture)
    - [📦 Post](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-post-back-to-architecture)
    - [📦 Notification](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-notification-back-to-architecture)
    - [📦 Moderation](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-moderation-back-to-architecture)
    - [📦 Auto Moderation](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-auto-moderation-back-to-architecture)
    - [📦 Moderation Handling](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-moderation-handling-back-to-architecture)
    - [📦 Storage](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-storage-back-to-architecture)
    - [📦 UI Framework](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-ui-framework-back-to-architecture)
    - [📦 Admin UI](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-admin-ui-back-to-architecture)
- [🧰 Setup](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#-setup)

## 🧭 What is the Collaborative Services?

Welcome to the Collaborative Services project — a powerful platform designed to streamline teamwork, data sharing, and service integration in complex environments. Whether you're building applications, sharing geospatial datasets, or coordinating with multiple stakeholders, this platform provides a unified workspace to manage assets, access computing resources, and collaborate in real time.

![Collaborative Home Page](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/Collab_home.JPG?raw=true)
With a focus on interoperability, user experience, and scalability, the Collaborative Services environment enables users to explore a rich catalog of datasets, models, tools, and documentation — all in one place.

![Collaborative Catalogue Page](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/fc885201141f5becc04b75d326dce4762b61d854/Collab_catalogue.JPG?raw=true)

## ⚙️ Technical description
### 🗺️ Architecture
The Microservices that make up the Collaborative platform project are the following: 
- **Authentication** (to be provided by each contributor)
- **Collaborative UI** [📄Description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main?tab=readme-ov-file#-what-is-the-collaborative-ui-back-to-architecture) [🔗Repository](https://github.com/acri-st/collaborative-ui)
- **Asset management** [📄Description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-asset-management-back-to-architecture) [🔗Repository](https://github.com/acri-st/asset-management)
- **Recommendation** [📄Description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-recommendation-back-to-architecture) [🔗Repository](https://github.com/acri-st/recommendation)
- **Search** [📄Description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-search-back-to-architecture) [🔗Repository](https://github.com/acri-st/search)
- **Discussion** [📄Description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-discussion-back-to-architecture) [🔗Repository](https://github.com/acri-st/discussion)
- **Geo extractor** [📄Description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-geo-extractor-back-to-architecture) [🔗Repository](https://github.com/acri-st/asset-geo-extractor)
- **Post** [📄Description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-post-back-to-architecture) [🔗Repository](https://github.com/acri-st/post)
- **Notification** [📄Description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-notification-back-to-architecture) [🔗Repository](https://github.com/acri-st/notification)
- **Moderation** [📄Description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-moderation-back-to-architecture) [🔗Repository](https://github.com/acri-st/moderation)
- **Auto moderation** [📄Description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-auto-moderation-back-to-architecture) [🔗Repository](https://github.com/acri-st/automoderation)
- **Moderation handling** [📄Description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-moderation-handling-back-to-architecture) [🔗Repository](https://github.com/acri-st/moderation-handling)
- **Storage** [📄Description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-storage-back-to-architecture) [🔗Repository](https://github.com/acri-st/storage)
- **UI Framework** [📄Description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-ui-framework-back-to-architecture) [🔗Repository](https://github.com/acri-st/ui-fwk)
- **Admin UI** [📄Description](https://github.com/acri-st/DESP-AAS-Collaborative-Services/blob/main/README.md#-what-is-the-admin-ui-back-to-architecture) [🔗Repository](https://github.com/acri-st/admin-ui)

![Collaborative platform Architecture](https://github.com/acri-st/collaborative-ui/blob/main/docs/architecture.png?raw=true)  

### 📄 Microservices description

#### 📦 What is the Collaborative UI? [Back to Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)

The Collaborative UI is a web application that interfaces with the microservices that comprise the ecosystem. It provides users a comprehensible experience to find and use different services of the platform, and has collaboration at its heart.

The Collaborative UI also uses a common library and framework that contains interfaces to services and styling called the desp-ui-fwk.  

#### 📦 What is the Asset Management? [Back to Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)

The Asset Management service is a microservice that handles the lifecycle of data assets. It provides the infrastructure and tools necessary for users to create, update, retrieve, moderate, and publish assets such as datasets, models, applications, and more.

The Asset Management service handles:
- **Asset CRUD** Creating, updating, retrieving, and deleting assets
- **Moderation** Managing asset validation, publication, and rejection workflows
- **Publication** Publishing assets and registering them with the search engine
- **User Interactions** Supporting likes, bookmarks, and asset views
- **Integration** Working with other microservices like Storage, Search, and Auth  

#### 📦 What is the Recommendation? [Back to Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)

The Recommendation microservice is a specialized service designed to provide intelligent recommendations to users based on various data inputs and algorithms.

**Key Features:**
- **Personalized Recommendations**: Delivers tailored suggestions based on user history and preferences
- **Real-time Processing**: Provides instant recommendations as user interactions occur
- **Scalable Architecture**: Built to handle high volumes of recommendation requests efficiently
- **Integration Ready**: Seamlessly integrates with other microservices in the ecosystem
- **Configurable Algorithms**: Supports multiple recommendation algorithms and strategies

**Use Cases:**
- Content recommendations for media platforms
- Product suggestions for e-commerce applications
- Service recommendations for various platforms
- User matching and connection suggestions  

#### 📦 What is the Search? [Back to Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)

The Search microservice is a specialized service designed to provide advanced search capabilities for assets within the platform. It leverages Elasticsearch to deliver fast, scalable, and intelligent search functionality.

**Key Features:**
- **Full-text search** across asset metadata and content
- **Geographic search** with support for GeoJSON shapes and coordinate reference systems
- **Asset categorization** and filtering by type, source, and category
- **Scoring and ranking** based on relevance, popularity (likes, downloads, views), and user preferences
- **Real-time indexing** of new assets and metadata updates

**Supported Asset Types:**
- User-generated content
- System-generated assets
- Various document types with customizable metadata

**Technical Capabilities:**
- RESTful API endpoints for search operations
- Configurable search scoring algorithms
- Support for complex geographic queries
- Subscription-based access control  

#### 📦 What is the Discussion? [Back to Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)

The Discussion service is a microservice that enables communication around assets and posts. It provides the infrastructure and tools necessary for users to create, manage, and participate in discussions, topics, and posts related to assets.

The Discussion service handles:
- **Discussion Management** Creating and managing discussion categories linked to assets
- **Topic and Post Management** Creating, editing, and retrieving topics and posts
- **Moderation Integration** Sending posts and topics for moderation
- **Integration** Working with other  microservices like Asset Management, Auth, and Notification  

#### 📦 What is the Geo extractor? [Back to Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)

The Asset Geo Extractor is a microservice designed to extract and process geographical data from various asset sources. It provides functionality to:

- **Extract geographical coordinates** from asset metadata and content
- **Process and validate** geographic data using GeoJSON standards
- **Integrate with Elasticsearch** for efficient data storage and retrieval
- **Support async operations** for high-performance data processing
- **Handle multiple asset formats** and data sources

This microservice is part of a larger system architecture and works in conjunction with other services like the Search microservice to interact with elasticsearch, and an asset manager to provide comprehensive asset management capabilities.  

#### 📦 What is the Post? [Back to Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)

The Post service is a microservice that enables communication around assets and posts. It provides the infrastructure and tools necessary for users to create, manage, and participate in discussions, topics, and posts related to assets.

The Post service handles:
- **Discussion Management** Creating and managing discussion categories linked to assets
- **Topic and Post Management** Creating, editing, and retrieving topics and posts
- **Moderation Integration** Sending posts and topics for moderation
- **Integration** Working with other  microservices like Asset Management, Auth, and Notification  

#### 📦 What is the Notification? [Back to Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)

The Notification microservice is a dedicated service responsible for handling all notification-related operations within the system. It provides a centralized solution for sending various types of notifications including emails, SMS, and push notifications.

**Key Features:**
- **Email Notifications**: Sends transactional and marketing emails
- **Queue-based Processing**: Uses RabbitMQ for reliable message handling
- **Scalable Architecture**: Designed to handle high-volume notification requests
- **Template Support**: Supports customizable notification templates
- **Delivery Tracking**: Monitors notification delivery status

The microservice operates independently, ensuring that notification failures don't impact other system components while providing reliable delivery mechanisms for critical communications.  

#### 📦 What is the Moderation? [Back to Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)

The Moderation microservice handles content moderation and validation. It provides manual review capabilities to ensure content quality, compliance, and safety across the platform.

**Key Features:**
- **API Integration**: RESTful API endpoints for seamless integration with other microservices and Admin UI

**Use Cases:**
- Reviewing user-generated content before publication
- Filtering inappropriate or non-compliant materials
- Ensuring data quality and consistency
- Supporting community guidelines enforcement  

#### 📦 What is the Auto Moderation? [Back to Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)

The AutoModeration microservice is a component designed to automatically analyze and moderate content. It provides content filtering capabilities to ensure compliance with organizational policies and standards.

**Key Features:**
- **Automated Content Analysis**: Uses AI (detoxify) to detect inappropriate or non-compliant content
- **Real-time Processing**: Provides feedback on content submissions
- **Configurable Rules**: Supports customizable moderation policies and thresholds
- **Scalable Architecture**: Built as a microservice for easy integration and horizontal scaling

**Use Cases:**
- User-generated content moderation
- Document and file screening
- Compliance monitoring
- Quality assurance automation  

#### 📦 What is the Moderation Handling? [Back to Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)

The Moderation-handling microservice is responsible for redirecting moderation events in real-time, providing moderation management tools for distributed systems.

**Key Features:**
- **Event Processing**: Handles incoming moderation events from various sources
- **Real-time Processing**: Provides low-latency event handling for time-sensitive operations
- **Scalable Architecture**: Built to handle high-volume event streams efficiently

**Use Cases:**
- Real-time event monitoring and alerting
- Policy enforcement across distributed systems  

#### 📦 What is the Storage? [Back to Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)

The Storage service is a microservice that handles file storage and repository management. It provides the infrastructure and tools necessary for users to store, manage, and access files, Git repositories, and metadata associated with their projects.

The Storage Management service handles:
- **Git Repository Management** Creating, managing, and accessing Git repositories for project files
- **File Storage** Storing and retrieving files with support for various formats and binary content
- **Metadata Management** Handling thumbnails, avatars, and other metadata associated with assets
- **Image Processing** Resizing, cropping, and optimizing images for thumbnails and avatars
- **Content Delivery** Streaming file content and serving static assets
- **Integration** Working with other microservices like Asset Management and Auth

#### 📦 What is the UI framework? [Back to Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)

The UI framework is the library that is used in collaborative-ui, sandbox-ui and admin-ui for utilities, React components, API interfaces, typings and more.  

#### 📦 What is the Admin UI? [Back to Architecture](https://github.com/acri-st/DESP-AAS-Collaborative-Services/tree/main#%EF%B8%8F-architecture)

The admin UI is a web application that interfaces with the microservices that comprise the collaborative platform and the sandbox for administrators to manipulate and moderate.  

## 🧰 Setup

See each microservice's README for local development instructions.  
