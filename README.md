# ASGI frameworks
You can use Uvicorn, Daphne, or Hypercorn to run any ASGI framework.

For small services you can also write ASGI applications directly.

ASGI (Asynchronous Server Gateway Interface) frameworks in Python vary in terms of performance, features, and complexity. While it's challenging to definitively rank them from fastest to slowest since performance can depend on many factors, I can provide a list of some popular ASGI frameworks, along with brief descriptions, starting with some of the most widely recognized for their speed and scalability:

1. **FastAPI**:
   - Known for its exceptional performance and automatic OpenAPI documentation generation.
   - Built on top of Starlette and Pydantic.
   - Utilizes Pydantic models for input validation and serialization.
   - Provides an easy-to-use and highly performant framework for building APIs.

2. **Starlette**:
   - A lightweight ASGI framework used as a foundation for other frameworks like FastAPI.
   - Known for its speed and simplicity.
   - Primarily focuses on routing and handling HTTP requests and responses.

3. **Tornado**:
   - An older, battle-tested asynchronous framework that predates ASGI.
   - Offers good performance and is well-suited for building WebSocket applications.
   - Known for its non-blocking I/O and event-driven architecture.

4. **Sanic**:
   - An ASGI framework designed for high performance.
   - Uses async/await syntax for handling requests.
   - Known for its speed, particularly for lightweight applications.

5. **Quart**:
   - A framework that is API-compatible with Flask but supports ASGI for asynchronous execution.
   - Provides a familiar Flask-like API with support for async/await.
   - Offers good performance and flexibility.

6. **Bocadillo**:
   - A microframework built on top of Starlette.
   - Focused on simplicity and productivity.
   - Suitable for building asynchronous web applications and APIs.

7. **Channels (Django Channels)**:
   - Extends Django to support real-time functionality like WebSockets.
   - Known for its reliability and compatibility with the Django ecosystem.
   - Provides a combination of synchronous and asynchronous views.

8. **Responder**:
   - An ASGI framework inspired by Flask and Falcon.
   - Designed for rapid API development.
   - Offers asynchronous capabilities and automatic serialization.

9. **Django with Channels**:
   - Django, a synchronous framework, can be used with Channels to add asynchronous functionality.
   - Suitable for building real-time applications alongside traditional web applications.
  
10. **Quart**:
    - Quart is a Flask-like ASGI web framework.  

11. **BlackSheep**:
     - BlackSheep is a web framework based on ASGI, inspired by Flask and ASP.NET Core.
     - Its most distinctive features are built-in support for dependency injection, automatic binding of parameters by request handler's type annotations, and automatic generation of OpenAPI documentation and Swagger UI.

12. **Falcon**:
     - Falcon is a minimalist REST and app backend framework for Python, with a focus on reliability, correctness, and performance at scale.

12. **Muffin**:
     - Muffin is a fast, lightweight and asynchronous ASGI web-framework for Python 3.

Please note that the choice of framework should not only depend on performance but also on factors like ease of use, community support, the specific requirements of your project, and your familiarity with the framework. Performance can also vary based on how well your code is optimized, your server configuration, and the workload of your application. Therefore, it's essential to consider your project's unique needs when selecting an ASGI framework.
