# Django REST Framework Book API

This is a **learning project** where I implemented features using Django Rest Framework (DRF) with a simple `Book` model. The project allows users to list, create, update, and delete books. It also implements authentication to restrict certain actions to logged-in users.

## What I Learned

1. **Model and Serializer Creation**:
   - I created a `Book` model with fields: `title`, `author`, and `published_date`.
   - Built a `BookSerializer` to convert model data into JSON format and handle input validation for API requests.

2. **Viewsets in DRF**:
   - I learned how to implement `ModelViewSet`, which provides built-in methods for `GET`, `POST`, `PUT`, and `DELETE` operations without writing custom views.
   - The `BookViewSet` handles both listing all books and creating new books.

3. **Routing with DefaultRouter**:
   - Used DRF’s `DefaultRouter` to automatically generate routes for my API.
   - Learned how to set up URLs like `/api/books/` for listing and creating books.

4. **Applying Permissions**:
   - Implemented `IsAuthenticatedOrReadOnly` permission class to ensure that only authenticated users can create, update, or delete books, while everyone can view the books.
   - Gained understanding of how DRF handles permissions and user authentication.


