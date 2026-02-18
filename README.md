# Cluster API (CAPI) mit Kubernetes

**Cluster API (CAPI)** ist ein Kubernetes-Projekt zur deklarativen Verwaltung von Kubernetes-Clustern selbst – also *„Kubernetes zum Managen von Kubernetes“*.

Es wurde ursprünglich von der Kubernetes SIG Cluster Lifecycle entwickelt und ist heute ein offizielles Subprojekt von Kubernetes.

## Kurzbeschreibung

Cluster API erweitert Kubernetes um eigene Ressourcen (Custom Resource Definitions), mit denen sich komplette Cluster definieren und verwalten lassen – ähnlich wie Pods oder Deployments.

Statt Cluster manuell zu erstellen, beschreibt man sie deklarativ in YAML-Dateien:

- Cluster  
- Control Plane  
- Worker Nodes  
- Infrastruktur (z. B. AWS, Azure, vSphere)

Kubernetes sorgt dann automatisch dafür, dass der gewünschte Zustand hergestellt wird.

## Vorteile

- Automatisierte Erstellung und Skalierung von Clustern  
- Einheitliches API-Modell über verschiedene Cloud-Anbieter  
- Declarative Infrastructure (GitOps-fähig)  
- Lifecycle-Management (Upgrades, Reparaturen, Skalierung)

## Typische Use Cases

- Multi-Cluster-Management  
- Kubernetes-Cluster in Cloud-Umgebungen  
- On-Premises-Installationen  
- Plattform-Engineering

> **Kurz gesagt:**  
> Cluster API ermöglicht es, Kubernetes-Cluster genauso zu verwalten wie Anwendungen innerhalb eines Clusters – deklarativ, automatisiert und cloud-unabhängig.


kubeadm -> installer für basic kubernetes

SIG -> Special intrest group, behandeln einen gewissen Apsekt des Clusters

CAPI verwaltet nur die Cluster hülle.