# Overview

This is a basic HTML website project containing a single static web page, now configured to run in the Replit environment. The project serves a simple static website with a heading and paragraph content. The HTML includes analytics tracking code for client-side monitoring.

# Recent Changes (August 29, 2025)
- Set up Node.js HTTP server to serve static content on port 5000
- Configured workflow for automatic server startup
- Added deployment configuration for production deployment
- Server configured with cache-control headers to prevent caching issues

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Static HTML**: Single-page static website using basic HTML structure
- **Server**: Node.js HTTP server serving static content
- **Port Configuration**: Frontend serves on port 5000 with host 0.0.0.0
- **Cache Control**: No-cache headers to prevent Replit iframe caching issues

## Development Setup
- **Runtime**: Node.js 20
- **Server File**: server.js handles HTTP requests and static file serving
- **Workflow**: "Static Website Server" workflow runs the Node.js server
- **Development Server**: Configured to serve on 0.0.0.0:5000 for Replit environment

## Page Structure
- **Document Type**: Standard HTML5 DOCTYPE declaration
- **Basic Layout**: Simple structure with head and body sections
- **Content Elements**: Single h1 heading and paragraph element

## Analytics Integration
- **Client-Side Tracking**: Includes embedded JavaScript variables for analytics monitoring
- **Tracking Variables**: Contains NS_CSM (likely namespace client-side monitoring) variables with IDs and URL paths

## Deployment Configuration
- **Target**: Autoscale deployment (stateless website)
- **Command**: node server.js
- **Production Ready**: Configured for Replit deployment

# External Dependencies

## Runtime Dependencies
- **Node.js**: Version 20 for running the HTTP server
- **Built-in Modules**: Uses Node.js http, fs, and path modules (no external packages required)

## Analytics/Monitoring Service
- **Service**: Unknown analytics platform (based on NS_CSM variable naming convention)
- **Purpose**: Client-side monitoring and data collection
- **Implementation**: Embedded JavaScript variables for tracking configuration

## Browser Dependencies
- **Target**: Standard web browsers supporting HTML5
- **Requirements**: JavaScript-enabled browsers for analytics functionality