# Kubernetes Examples

Este repositorio contiene ejemplos prácticos relacionados con
Kubernetes, organizados en distintos manifiestos YAML y estructuras de
recursos típicos de un clúster.

## Objetivo

El propósito de este repositorio es servir como:

-   Colección de ejemplos básicos y avanzados de Kubernetes.
-   Referencia rápida de manifiestos YAML.
-   Entorno de pruebas para comprender cómo funcionan los distintos
    recursos del clúster.
-   Material de apoyo para aprendizaje y experimentación.

## Contenido del repositorio

El repositorio incluye distintos tipos de recursos comunes en
Kubernetes, como por ejemplo:

-   Pods
-   Deployments
-   Services
-   ReplicaSets
-   ConfigMaps
-   Volúmenes
-   Otros manifiestos relacionados con la administración del clúster

Cada archivo YAML representa un recurso específico que puede aplicarse
directamente a un clúster Kubernetes.

## Requisitos

Para probar los ejemplos necesitas:

-   kubectl instalado
-   Acceso a un clúster Kubernetes (por ejemplo: Minikube, Kind, Docker
    Desktop o un clúster remoto)

## Cómo usar los ejemplos

1.  Clona el repositorio:

    git clone https://github.com/dgarridouma/kubernetes.git

2.  Accede al directorio:

    cd kubernetes

3.  Aplica un manifiesto específico:

    kubectl apply -f nombre-del-archivo.yaml

4.  Verifica los recursos creados:

    kubectl get all

Para eliminar los recursos:

kubectl delete -f nombre-del-archivo.yaml
