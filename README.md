# Yorkster Terminal

Yorkster Terminal is a modular PowerShell-like terminal platform where files represent runtime objects.

## Core Idea

The system uses a structured architecture where file extensions correspond to runtime types.

Example:

.tmm1 → Yorkster.Terminal.Module

## File Formats

.tm1 — terminal script  
.tmm1 — module package  
.tmdt1 — module data  
.tmmdcmt1 — module documentation  
.tmmdcmtmgmt1 — documentation management

## Command System

Commands are divided into three categories:

- System category
- Module category
- Alias category

## Module System

Modules are distributed as single files:

.tmm1

Each module contains:

- manifest
- commands
- module data
- documentation references

## Development

Language: C++

Core components:

- parser
- shell
- type loader
- platform APIs

## Status

Early development.
Core architecture defined.
