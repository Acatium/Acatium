Product and technology leader who still builds. I'm currently taking an AI-native consumer
product from zero to one as its founder, with AI coding agents doing most of the
implementation against specs I write. The repos here are earlier prototypes, where I test
product and architecture bets before committing a team to them.

## Projects

**[federation](https://github.com/Acatium/federation)**: federated data governance across
AWS, Databricks, and Snowflake. Platform-native access policies are mirrored into Apache
Ranger, with metadata federated through Gravitino and queries run through Trino. The core is
a computed safety model that shows a policy sync gap can cause noise, but not a data leak.
*Python · Trino · Ranger · Gravitino · Arrow Flight SQL*

**[ALEC](https://github.com/Acatium/ALEC)**: a multi-agent knowledge-discovery system built
on the blackboard pattern. The shared knowledge graph is the coordination medium, a
stateless coordinator is rebuilt every cycle, and a human can steer the agents mid-run.
*Python · asyncio · PostgreSQL + pgvector · Claude · React*

**[alec-learning-loop](https://github.com/Acatium/alec-learning-loop)**: the earlier design
(v4) of ALEC, an agent memory that learns from feedback. It picks lessons by Thompson
sampling, attributes outcomes to the lessons used, and includes a statistical evaluation
harness to test whether the loop actually helps.
*Python · Kafka · Redis · PostgreSQL*

The two ALEC repos show one design decision in sequence: the v4 event-driven stack was easy
to reason about but heavy to run, so v5 collapsed it to PostgreSQL-only.

