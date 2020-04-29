# net-core-superpowers-202004-brendan
In April 2020, we ran a ".NetCore superpowers" day online with Brendan Richards and Jason Taylor

This repo contains Brendan's Demos

## Hello
To start the day, brendan crated a simple console app

## mvc
We fiollowed this by creating an asp.net core mvc app and walked through the code you get.

## casln
This app is based on Jason Taylor's Clean Architecture Solution Template. 

it contains added samples for:
- An EF Core Migration
- a 2nd 'Todo' exmale that uses Signal R to sync list item changes
- A Blazor Client UI sample that fetches weather data from the main webUI Rest API
- A GRPC server example

## Weather Console
A small console app to demonstrate connectiong to the above Grpc example as a client.
