# Lab3 - Apache Kafka

TP simple sur Apache Kafka avec des exemples de base.

## Contenu

- Producteur/Consommateur Kafka en Java
- Commandes Kafka en ligne de commande
- Exemple Kafka Connect

## Commandes principales

```
# Démarrer Kafka
./start-kafka-zookeeper.sh

# Créer un topic
kafka-topics.sh --create --bootstrap-server localhost:9092 --topic test

# Tester la production
kafka-console-producer.sh --bootstrap-server localhost:9092 --topic test

# Tester la consommation
kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic test --from-beginning

Auteur
YOUSSEFBT369


**Pour ajouter :**
```bash
echo "# Lab4 - Apache Kafka

TP simple sur Apache Kafka avec des exemples de base.

## Contenu
- Producteur/Consommateur Kafka en Java
- Commandes Kafka en ligne de commande
- Exemple Kafka Connect

## Commandes principales
\`\`\`bash
# Démarrer Kafka
./start-kafka-zookeeper.sh

# Créer un topic
kafka-topics.sh --create --bootstrap-server localhost:9092 --topic test

# Tester la production
kafka-console-producer.sh --bootstrap-server localhost:9092 --topic test

# Tester la consommation
kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic test --from-beginning
\`\`\`

## Auteur
YOUSSEFBT369" > README.md

git add README.md
git commit -m "Ajout README simple"
git push
