---
title: Agents management
linkTitle: Agents management
weight: 20
date: 2024-10-10
---

In Topology, agents configured within your organization can be viewed to identify if any actions are to be taken.

## View available agents

Only the Central Admin can view the *agents list*.

1. Navigate to *Topology > Environments > Agents*. There are five cards in the *agents list* view: Connected, Unhealthy, Stopped, Update Available, and Unsupported.

{{< alert title="Note" color="primary" >}}If there are unsupported agents, an alert/banner will appear at the top of the screen. Follow the provided instructions on how to upgrade your agents, or see the [upgrade procedures](/docs/connect_manage_environ/connected_agent_common_reference/upgrade_agent) documentation and view the [latest agent versions in the release notes](/docs/amplify_relnotes).{{< /alert >}}

{{< alert title="Tip" color="secondary" >}}The list of agents can be filtered by Dataplanes, Hosting, Agent State, Version Status and Last Activity by using the filter located at the left of the screen.{{< /alert >}}

A list of agents is displayed with the following information:

* **Agent State** - displays the current state of the agent. Can be one of three states: Connected, Unhealthy, or Stopped.

    * **Connected** - the agent is running smoothly and has been updated in the last 24 hours.
    * **Unhealthy** -  the agent is in a unhealthy or failed state and/or has not communicated in the last 24 hours or more.
    * **Stopped** - the agent is no longer functioning.

* **Agent Name** - the title of the agent.
* **Agent Version** - the agent version number.
* **Agent Type** - can be either a Discovery Agent or a Traceability Agent.
* **Agent Host** - can be either On-premise or SaaS (embedded agent).
* **Agent Version Status** - applies to on-premise agents only. Provides information on the update status of the agent. Can have one of three statuses: Up To Date, Update Available, or Outdated. View the [latest agent vesions](/docs/amplify_relnotes).

    * **Up To Date** - the agent is up to date.
    * **Update Available** - a new version is available.
    * **Outdated** - the current version of the agent is outdated. If there are any unsupported agents, an alert/banner will appear at the top of the screen.
    * **Redacted** - the current version has been redacted. It is recommended to upgrade immediately. If there are any redacted agents, an alert/banner will appear at the top of the screen.

* **Environment** - the environment the agent is a part of.
* **Agent's Last Activity** - the last time the agent was updated. By default, this field is selected to show agents in descending order based upon the last activity time.

## View agent details

1. Navigate to *Topology > Agents*.
2. Click on the agent. *Basic details are displayed about the agent*.
