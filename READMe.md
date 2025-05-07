Flask E-commerce Application with Gunicorn

Python Project

📌Customers can sign in or sign up
📌Customers can reset their passwords
📌Customers can search for goods
📌Add them to their cart
📌Payment Gateway Functionality
📌Admins can regulate shop products e.g stock level
📌Admins can change order status


OVERVIEW

This Docker image packages a Flask-based e-commerce application, optimized for production use with Gunicorn. The lightweight python:3.8-slim base image ensures efficient and quick deployment.

FEATURES

Flask Framework: Robust and scalable web application built with Flask.
Gunicorn Server: High-performance WSGI server for running Python web applications.
Efficient: Slim Python base image minimizes overhead.

HOW TO USE 

docker pull monish247/ecommerce_python_image:latest   

docker run -itd -p 8034:80 monish247/ecommerce_python_image:latest

