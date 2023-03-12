# Python OnBoarding
## 1. Django
Follow the [Django](https://www.djangoproject.com/) tutorial and write your first Django app.

- [x] [Install Django and set up a database](https://docs.djangoproject.com/en/3.0/intro/install/).
- [x] [Create a project and an app](https://docs.djangoproject.com/en/3.0/intro/tutorial01/).
- [x] [Models & Migrations](https://docs.djangoproject.com/en/3.0/intro/tutorial02/).
- [x] [Views](https://docs.djangoproject.com/en/3.0/intro/tutorial03/).
- [x] [Generic Views](https://docs.djangoproject.com/en/3.0/intro/tutorial04/).
- [x] [Testing](https://docs.djangoproject.com/en/3.0/intro/tutorial05/).

## 2 REST
Learn the basics about REST (https://restfulapi.net/).

Read the following sections / topics:
- [x] Learn REST (the whole section).
- [x] Idempotence.
- [x] Put vs Post.

Also, check out and keep as a reference [Best Practices for Designing a Pagmatic RESTful API](https://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api).

## 3. Django REST Framework
[Django REST Framework](https://www.django-rest-framework.org/)'s (DRF) website has an in-depth tutorial as well as great documentation.

Follow DRF’s official tutorial, which covers the main features of the framework.

- [x] [Serialization](https://www.django-rest-framework.org/tutorial/1-serialization/).
- [x] [Requests & Responses](https://www.django-rest-framework.org/tutorial/2-requests-and-responses/).
- [x] [Classs-based Views](https://www.django-rest-framework.org/tutorial/3-class-based-views/).
- [x] [Authentication & Permissions](https://www.django-rest-framework.org/tutorial/4-authentication-and-permissions/).
- [x] [Relationships & Hyperlinked APIs](https://www.django-rest-framework.org/tutorial/5-relationships-and-hyperlinked-apis/).
- [x] [ViewSets & Routers](https://www.django-rest-framework.org/tutorial/6-viewsets-and-routers/).

Check out and keep as a reference [Classy Django REST Framework](http://www.cdrf.co/)

## 4. Authentication
- [x] Investigate about JWT
- [x] Check out and keep as a reference [DRF Authentication](https://www.django-rest-framework.org/api-guide/authentication/).
- [x] Install [djangorestframework-simplejwt](https://django-rest-framework-simplejwt.readthedocs.io/en/latest/index.html) in your project, skim through the documentation and keep it as a reference.
- [x] Implement `sign_up` and `sign_in` endpoints.
- [x] Implement email verification for new users.

## 5. DRF Testing
Read the following resources:
- [x] [DRF Testing](https://www.django-rest-framework.org/api-guide/testing).
- [x] [How to Develop APIs with Django REST Framework](https://djangostars.com/blog/rest-apis-django-development/) is a DRF tutorial that covers topics already seen but using a TDD. It has useful examples of testing and documenting in DFR.
- [x] [Testing for Django Rest Framework with Factory Bot and Faker](https://ruddra.com/posts/tdd-drf-factory-boy-faker/).

Implement unit tests in your tutorial's application.
- [x] Implement tests for the models.
- [x] Implement tests for the API.

## 6. Design the "moovie" API
Take a look at this [diagram]( https://drive.google.com/open?id=1oecuuhaecnH4TNOpXp3Q8St0PQ6Am2L0) (open it with StarUML):

Based on that model, design an API that supports the following operations:

Movies:
- [x] List movies (supporting paging, filtering, and sorting).
- [x] Get movie.

Lists:
- [x] Get user lists.
- [x] Create list.
- [x] Get list.
- [x] Update list.
- [x] Delete list.
- [x] Add movie to list.
- [x] Remove movie from list.

Genres:
- [x] Get genres.

User profile:
- [x] Get user profile.
- [x] Update user profile.
- [x] Upload user photo.
- [x] Remove user photo.

For each one of the above operations, you should specify:
- HTTP method.
- HTTP path.
- path parameters.
- query parameters parameters.
- Possible HTTP response codes.
- Success response schema.
- Error response schema.

NOTE: Don't design for authentication / authorization in mind. These topics will be covered later.

