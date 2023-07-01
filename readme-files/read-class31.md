# Key components of a Docker container: Docker containers consist of three main components:

> a) Docker Image: A lightweight, standalone, executable package that includes everything needed to run a piece of software, including code, runtime, libraries, and dependencies.

> b) Docker Container: An instance of a Docker image that runs as a process on the host machine, isolated from other containers and the underlying system.

> c) Docker Registry: A repository that stores Docker images, allowing easy distribution and sharing of containerized applications.

>How they streamline development and deployment: Docker containers provide consistent environments across different stages of the application development and deployment lifecycle, making it easier to develop, test, and deploy applications. They encapsulate the application and its dependencies, ensuring that it runs the same way on any environment. This streamlines the development process, reduces compatibility issues, and simplifies the deployment process, as containers can be easily moved between environments.

# Primary steps to build a library website using Django:

>a) Models: Define the data structure of the library, such as books, authors, and users, using Django's model classes to create database tables and relationships.

>b) Views: Create views that handle user requests, retrieve data from the models, and render templates to display the library's information.

>c) Templates: Design HTML templates to define how the library website will look, including dynamic placeholders to display data fetched from the views.

>d) URL Patterns: Map URLs to corresponding views using Django's URL patterns, defining the navigation flow of the website.

>e) Static Files: Organize and serve static files (e.g., CSS, JavaScript) to style and enhance the website's frontend.

>f) Admin Interface: Optionally, enable Django's built-in admin interface to manage the library's data easily.

# Primary differences between Django and Django REST framework:

## Django:

>Django is a high-level web framework primarily used for building full-stack web applications.

>It includes an Object-Relational Mapping (ORM) system for working with databases and models.

>Django provides built-in form handling, templating, authentication, and admin interface for application development.

>It follows the Model-View-Template (MVT) architectural pattern.

## Django REST framework:

>Django REST framework is an extension of Django that focuses on building Web APIs for applications.

>It includes features specifically tailored for creating RESTful APIs, such as serializers for data serialization/deserialization.

>Django REST framework provides powerful tools for authentication, permissions, throttling, and versioning of APIs.

>It follows the Model-View-Serializer (MVS) architectural pattern, which is an extension of the MVT pattern, optimized for API development.