# Convex Cursor Rules

A collection of AI rules for [Cursor](https://cursor.sh/) IDE to enhance development with [Convex](https://www.convex.dev/), providing intelligent assistance through Model-Code-Prompt (MCP) workflows.

## Overview

These rules help automate common Convex development tasks and provide intelligent suggestions for schema design, query optimization, data modeling, migrations, and more.

## Installation

1. Clone this repository or download the files
2. Copy the `.cursor` directory to your Convex project root
3. Restart Cursor to load the new rules

## Available Rules

### 1. Schema Analyzer

Analyzes existing database documents and suggests schema improvements based on actual data stored in the database. Identifies missing fields, suggests proper types, and recommends validation rules.

### 2. Query Optimizer

Analyzes Convex queries and suggests optimizations for better performance, including proper use of indexes, pagination strategies, and identifying N+1 query problems.

### 3. Function Categorizer

Helps categorize Convex functions properly as queries, mutations, or actions based on their behavior and side effects, ensuring they follow Convex's execution guarantees.

### 4. Real-time Data Analyzer

Optimizes real-time data subscriptions in Convex applications, suggesting improvements for subscription granularity and client-side performance.

### 5. Migration Assistant

Provides assistance with planning and implementing safe schema migrations, including generating migration functions and recommending phased approaches for large-scale changes.

### 6. Auth Pattern Optimizer

Analyzes and improves authorization patterns in Convex applications, suggesting optimized patterns and identifying potential security issues.

### 7. Data Modeling Guide

Provides best practices for Convex database design, recommending normalization or denormalization strategies and improved relationships between tables.

### 8. Index Analyzer

Automatically analyzes query patterns and suggests optimal indexes for better performance.

## Usage

These rules are automatically triggered as you work with Convex in Cursor. For example:

1. When working on schema files, the Schema Analyzer will suggest improvements
2. When writing queries, the Query Optimizer will recommend performance enhancements
3. When implementing authentication, the Auth Pattern Optimizer will suggest best practices

You can also explicitly ask Cursor AI for help with specific Convex tasks, and it will use these rules to provide assistance.

## Contributing

Contributions are welcome! Feel free to submit pull requests with new rules or improvements to existing ones.

## License

MIT 