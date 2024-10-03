## What is the application doing?

Jede Minute eine Quote ausgeben.

## Which programming language is used for the backend?

Python

## Which programming language is used for the frontend?

React JavaScript

## To which resource type does the Route forward it’s request to?

Service

## How does a Service know, to which Pod’s it need to forward requests to?

Selector bei quotes-deployment.yaml

## Who creates the requests to the Backend? The Frontend or the Browser?

The Browser

## How does the backend know to which database it needs to connect?

Durch die Umgebungs Variable DB_SERVICE_NAME

## What does a HPA do?

Es skaliert die Webseite, je nach dem wie viel Anfragen man bekommt.

## Why can a HPA be useful?

Wenn sehr viele user, die Platform benötigen kann es automatisch hoch skalieren

## What could be the risk of using a HPA?

Falls Attacke, unnötig Ressourcen verschwenden, falls HPA zu tief eingstellt.
