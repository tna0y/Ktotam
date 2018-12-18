# Ktotam
Stateful WAF with turing-complete rules

## Description

The core idea of this project is to build a network filtering platform which will be able to process *HTTP* traffic with extreme level of expression and with little to no knowledge of undelying web app architecture.

## Core principles

  * Rule expression: User should be able to do absolutely anyting in rules' code.
  * Fast deployment: User should be able to deploy Ktotam in a few commands.
  * Embeddability: Ktotam should be a platform which may be easily used from within other code.

## Example use cases

  * Hotfix a complex logic bug exposing a security vulnerability.
  * Build a ML security solution looking for anomalies in HTTP traffic.
  
