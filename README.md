# Ludus Range Configs

A collection of ready-to-use Ludus blueprints for building realistic lab environments across defensive, offensive, and enterprise administration scenarios.

## What’s included

This repository contains four blueprint sets:

- ADLab MSSQL — Active Directory plus Microsoft SQL Server for identity and database-focused exercises.
- Multi-Tool Red Team Lab — A red-team environment built around Vectr, Caldera, Mythic, and Ghostwriter.
- Red Team Operations Lab — A focused operations range for command-and-control and offensive tooling.
- SCCM Lab — An enterprise management lab with SCCM site roles and supporting Windows infrastructure.

## Quick Start

```bash
# Add this source to your Ludus server via an interactive installer
ludus source add https://github.com/5tuk0v/ludus_range_configs

# Or, script the install of source resources
ludus source add https://github.com/5tuk0v/ludus_range_configs --all

# Choose a blueprint to deploy
ludus blueprint apply 5tuk0v/blue-lab

# Watch Ludus work
ludus range deploy
ludus range logs -f
```
