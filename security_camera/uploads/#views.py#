from django.shortcuts import render
from django.views.generic import ListView, CreateView
from .models import Post

from .forms import PostForm
from django.urls import reverse_lazy

# Create your views here.
class HomePageView(ListView):
    model = Post
    template_name = "home.html"

class CreatePostView(CreateView):
    model = Post
    form_class = PostForm
    template_name = "post.html"
    success_url = "/post"  # reverse_lazy("uploads")
