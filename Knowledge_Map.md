# Internship Knowledge Map

## Technical Architecture & Frameworks

### ReAct Architecture
- [Design and Implementation of an Intelligent Regulatory Compliance Review System](English_Internship_Logs/36.md) - Introduces the basic principles and implementation of ReAct (Reasoning + Acting) architecture
  - Reasoning-Action-Observation loop
  - Think-Tool Call-Result Processing design pattern
  - Multi-turn conversation management
- [Design and Implementation of an LLM-Based Intelligent Advertisement Review System](English_Internship_Logs/37.md) - Demonstrates the application of ReAct architecture in advertisement review
  - Scene recognition module design
  - Parallel tool calling implementation
  - Result merging and final decision making
- [Building a Reliable LLM Tool Calling System](English_Internship_Logs/41.md) - Explores in-depth the reliability issues in tool calling within ReAct architecture
  - Tool call state management
  - Result validation and consistency guarantees
  - Early stopping strategies and efficiency optimizations

### Modular System Design
- [Design and Implementation of an Intelligent Regulatory Compliance Review System](English_Internship_Logs/36.md) - Introduces layered modular design
  - Collaboration between rule parser, review controller, and tool integration layer
  - Interface design between modules
- [Health Food Advertisement Intelligent Review System](English_Internship_Logs/40.md) - Demonstrates layered design in complex business systems
  - Division into access layer, business layer, model layer, and infrastructure layer
  - Responsibilities and collaboration mechanisms between layers
- [Design and Implementation of an LLM-Based Intelligent Advertisement Review System](English_Internship_Logs/37.md) - Discusses inter-module communication and integration
  - Collaboration between scene recognition module, rule parsing module, and ReAct controller
  - Asynchronous communication mechanisms

### FastAPI Application Development
- [FastAPI Image Comparison Development and Optimization](English_Internship_Logs/26.md) - Introduces basic application of FastAPI framework
  - Route definition and parameter validation
  - Asynchronous processing capabilities
  - Dependency injection system
- [FastAPI System Error Handling and Robustness Optimization](English_Internship_Logs/29.md) - Discusses error handling mechanisms in FastAPI in detail
  - Global exception handlers
  - Middleware design
  - Response model standardization
- [Health Food Advertisement Intelligent Review System](English_Internship_Logs/40.md) - Demonstrates FastAPI application in complex business systems
  - Large application structure organization
  - API version management
  - File upload and processing

## Large Language Model Applications

### Prompt Engineering
- [Design and Implementation of an Intelligent Regulatory Compliance Review System](English_Internship_Logs/36.md) - Introduces template-based prompt management
  - Template design principles
  - Dynamic parameter replacement
  - Context management
- [Building a Reliable LLM Tool Calling System](English_Internship_Logs/41.md) - Discusses in detail how to design prompts to guide LLMs to use tools correctly
  - Formatted tool usage instructions
  - Clear step-by-step guidance
  - Example-driven prompt design
- [Design and Implementation of an LLM-Based Intelligent Advertisement Review System](English_Internship_Logs/37.md) - Demonstrates the application of structured prompt templates
  - Task description optimization
  - Standardized tool descriptions
  - Output format control
- [Rule Structure Optimization and Simplification](English_Internship_Logs/45.md) - Discusses how to design prompts for structured output
  - JSON format control techniques
  - Field constraint descriptions
  - Correspondence between prompt structure and output structure

### Tool Calling
- [Building a Reliable LLM Tool Calling System](English_Internship_Logs/41.md) - Analyzes in depth the reliability issues in LLM tool calling
  - Tool call parsing techniques
  - Result validation mechanisms
  - Retry and fault tolerance handling
- [Design and Implementation of an Intelligent Regulatory Compliance Review System](English_Internship_Logs/36.md) - Demonstrates the design of the tool integration layer
  - Tool registration mechanisms
  - Parameter validation and conversion
  - Result standardization processing
- [Design and Implementation of an LLM-Based Intelligent Advertisement Review System](English_Internship_Logs/37.md) - Introduces tool calling implementation in the ReAct controller
  - Dynamic tool selection
  - Parameter construction
  - Result processing workflow
- [Health Food Advertisement Intelligent Review System](English_Internship_Logs/40.md) - Discusses domain-specific tool design and implementation
  - Logo detection tools
  - Text analysis tools
  - Compliance verification tools

### Multimodal Analysis
- [FastAPI Image Comparison Development and Optimization](English_Internship_Logs/26.md) - Introduces the application of vision language models in image analysis
  - Image feature extraction
  - Semantic-level comparison analysis
  - Similarity calculation methods
- [Design and Implementation of an LLM-Based Intelligent Advertisement Review System](English_Internship_Logs/37.md) - Demonstrates multimodal analysis in advertisement review
  - Combined text-image analysis
  - Multimodal content understanding
  - Cross-modal feature fusion
- [Health Food Advertisement Intelligent Review System](English_Internship_Logs/40.md) - Details the implementation of the image analysis module
  - Image preprocessing techniques
  - Feature extraction and matching
  - Image block processing optimization

### LLM Output Parsing and Post-processing
- [FastAPI Image Comparison Development and Optimization](English_Internship_Logs/26.md) - Discusses JSON output cleaning and standardization
  - Format repair techniques
  - Structure validation methods
  - Error recovery strategies
- [Building a Reliable LLM Tool Calling System](English_Internship_Logs/41.md) - Introduces tool call parsing techniques
  - String matching methods
  - Parsing error handling
  - Incremental parsing strategies
- [Design and Implementation of an LLM-Based Intelligent Advertisement Review System](English_Internship_Logs/37.md) - Demonstrates complex decision result extraction methods
  - Final result standardization
  - Evidence chain extraction
  - Explainability enhancement

## Data Processing & Validation

### Rule Parsing
- [Design and Evolution of a Rule Parser](English_Internship_Logs/42.md) - Details the design approach and evolution process of the rule parser
  - LLM integration with rule parsing
  - Parsing result validation
  - Incremental update mechanisms
- [Intelligent Segmentation Processing for Large-Scale Regulatory Texts](English_Internship_Logs/43.md) - Discusses technical solutions for processing large-scale regulatory texts
  - Intelligent segmentation algorithms
  - Context preservation strategies
  - Segment merging techniques
- [Design and Implementation of an Intelligent Regulatory Compliance Review System](English_Internship_Logs/36.md) - Introduces the basic functionality of the rule parser
  - Regulatory text structuring
  - Rule extraction and classification
  - Rule applicability assessment
- [Rule Structure Optimization and Simplification](English_Internship_Logs/45.md) - Analyzes in detail the evolution process of rule structures from complexity to simplicity
  - Structure redundancy analysis
  - Field optimization strategies
  - Data migration solutions

### Data Models
- [Rule Model Design Based on Pydantic](English_Internship_Logs/44.md) - Details building type-safe data models using Pydantic
  - Field validation mechanisms
  - Custom validators
  - Model nesting and composition
- [FastAPI Image Comparison Development and Optimization](English_Internship_Logs/26.md) - Demonstrates Pydantic data models in FastAPI applications
  - Request/response model design
  - Automatic model documentation generation
  - Model serialization and deserialization
- [Design and Evolution of a Rule Parser](English_Internship_Logs/42.md) - Discusses simplification and optimization of rule structures
  - Model evolution strategies
  - Backward compatibility guarantees
  - Model version management
- [Rule Structure Optimization and Simplification](English_Internship_Logs/45.md) - Shows the impact of data model optimization on system performance
  - Field selection and organization
  - Flattened structure design
  - Validation logic optimization

### Text Processing
- [Intelligent Segmentation Processing for Large-Scale Regulatory Texts](English_Internship_Logs/43.md) - Details text segmentation and context maintenance techniques
  - Rule-based segmentation
  - Dynamic length adjustment
  - Context window mechanisms
- [Python Implementation for Batch Residential Community Data Analysis](English_Internship_Logs/38.md) - Demonstrates address information extraction and text processing techniques
  - Address parsing algorithms
  - Data cleaning techniques
  - Information extraction strategies
- [Python Automation for Old Residential Community Analysis](English_Internship_Logs/39.md) - Introduces the application of regular expressions in text processing
  - Multi-level extraction strategies
  - Pattern matching optimization
  - Text data validation

### JSON Processing
- [FastAPI Image Comparison Development and Optimization](English_Internship_Logs/26.md) - Details JSON cleaning and standardization
  - Field repair techniques
  - Format standardization methods
  - Complex nested structure handling
- [Building a Reliable LLM Tool Calling System](English_Internship_Logs/41.md) - Discusses JSON parsing and validation
  - Partial parsing strategies
  - Error recovery mechanisms
  - Result validation techniques
- [Design and Evolution of a Rule Parser](English_Internship_Logs/42.md) - Demonstrates JSON data conversion and storage
  - Serialization optimization
  - Compression strategies
  - Version compatibility handling

## System Optimization & Best Practices

### Performance Optimization
- [Intelligent Segmentation Processing for Large-Scale Regulatory Texts](English_Internship_Logs/43.md) - Introduces parallel processing and cache optimization techniques
  - Task splitting strategies
  - Parallel execution control
  - Result merging mechanisms
- [Design and Evolution of a Rule Parser](English_Internship_Logs/42.md) - Discusses asynchronous processing and caching mechanisms
  - I/O-intensive operation optimization
  - Resource pool management
  - Asynchronous task scheduling
- [Health Food Advertisement Intelligent Review System](English_Internship_Logs/40.md) - Demonstrates optimization of image processing and concurrent processing
  - Image preprocessing optimization
  - Memory usage optimization
  - Concurrent request management
- [Rule Structure Optimization and Simplification](English_Internship_Logs/45.md) - Analyzes in detail the significant performance improvements from data structure optimization
  - Performance benefits of structure simplification
  - Parsing speed improvements
  - Storage space savings

### Error Handling
- [FastAPI System Error Handling and Robustness Optimization](English_Internship_Logs/29.md) - Details multi-level error handling mechanisms
  - Exception classification system
  - Global exception handlers
  - Error response standardization
- [Building a Reliable LLM Tool Calling System](English_Internship_Logs/41.md) - Discusses error handling in LLM tool calling
  - Parsing error handling
  - Tool execution error recovery
  - State consistency guarantees
- [Design and Implementation of an LLM-Based Intelligent Advertisement Review System](English_Internship_Logs/37.md) - Demonstrates multi-level exception catching and retry mechanisms
  - Tiered retry strategies
  - Timeout handling
  - Degradation mechanisms
- [Health Food Advertisement Intelligent Review System](English_Internship_Logs/40.md) - Introduces system-level error handling design
  - Error classification strategies
  - Logging standards
  - Monitoring and alerting integration

### Caching Strategies
- [Design and Evolution of a Rule Parser](English_Internship_Logs/42.md) - Introduces text hash-based caching mechanisms
  - Cache key design
  - Cache expiration strategies
  - Cache consistency guarantees
- [Intelligent Segmentation Processing for Large-Scale Regulatory Texts](English_Internship_Logs/43.md) - Discusses segment-level cache optimization
  - Fine-grained cache design
  - Cache hit rate optimization
  - Memory and persistent cache combination
- [Health Food Advertisement Intelligent Review System](English_Internship_Logs/40.md) - Demonstrates caching application for image analysis results
  - Multi-level cache design
  - Cache warming strategies
  - Cache update mechanisms
- [Building a Reliable LLM Tool Calling System](English_Internship_Logs/41.md) - Discusses LLM response caching optimization
  - Prompt hash caching
  - Result reuse strategies
  - Cache invalidation mechanisms

### Data Migration & Refactoring
- [Rule Structure Optimization and Simplification](English_Internship_Logs/45.md) - Details the design and implementation of data migration tools
  - Field mapping strategies
  - Incremental migration techniques
  - Data validation mechanisms
- [Design and Evolution of a Rule Parser](English_Internship_Logs/42.md) - Discusses refactoring strategies during system evolution
  - Gradual refactoring methods
  - Interface compatibility maintenance
  - Feature migration steps
- [Rule Model Design Based on Pydantic](English_Internship_Logs/44.md) - Demonstrates validation mechanisms in model refactoring
  - Data converters
  - Model compatibility layers
  - Validation logic migration

### Asynchronous Programming Patterns
- [FastAPI Image Comparison Development and Optimization](English_Internship_Logs/26.md) - Introduces asynchronous processing patterns in FastAPI
  - Asynchronous route design
  - Asynchronous dependency injection
  - Asynchronous context management
- [FastAPI System Error Handling and Robustness Optimization](English_Internship_Logs/29.md) - Discusses error handling in asynchronous systems
  - Asynchronous exception propagation
  - Task cancellation handling
  - Timeout management
- [Building a Reliable LLM Tool Calling System](English_Internship_Logs/41.md) - Demonstrates complex asynchronous flow control
  - Asynchronous state management
  - Asynchronous tool calling
  - Asynchronous result aggregation

## Testing & Monitoring

### Testing Strategies
- [FastAPI System Error Handling and Robustness Optimization](English_Internship_Logs/29.md) - Discusses system robustness testing methods
  - Exception injection testing
  - Boundary condition testing
  - Load testing
- [Building a Reliable LLM Tool Calling System](English_Internship_Logs/41.md) - Introduces LLM tool calling testing techniques
  - Tool response simulation
  - Exception scenario testing
  - Integration test design
- [Health Food Advertisement Intelligent Review System](English_Internship_Logs/40.md) - Demonstrates testing strategies for complex systems
  - Modular testing
  - End-to-end testing
  - Performance benchmark testing

### Logging & Monitoring
- [FastAPI System Error Handling and Robustness Optimization](English_Internship_Logs/29.md) - Details logging system design
  - Log level strategies
  - Structured logging
  - Contextual logging
- [Building a Reliable LLM Tool Calling System](English_Internship_Logs/41.md) - Discusses tool call logging and monitoring
  - Key point logging
  - Performance metric collection
  - Anomaly pattern detection
- [Health Food Advertisement Intelligent Review System](English_Internship_Logs/40.md) - Demonstrates multi-level monitoring systems
  - System monitoring
  - Business monitoring
  - Performance monitoring
  - Security monitoring

## Engineering Practices & Project Management

### Code Organization & Design Patterns
- [FastAPI Image Comparison Development and Optimization](English_Internship_Logs/26.md) - Introduces modular design and code organization
  - Service layering pattern
  - Separation of concerns principle
  - Dependency injection pattern
- [Building a Reliable LLM Tool Calling System](English_Internship_Logs/41.md) - Discusses the application of controller pattern in tool calling
  - State management pattern
  - Command pattern
  - Strategy pattern
- [Health Food Advertisement Intelligent Review System](English_Internship_Logs/40.md) - Demonstrates code organization for large systems
  - Modular design
  - Interface design principles
  - Configuration management strategies

### Version Management & Evolution
- [Design and Evolution of a Rule Parser](English_Internship_Logs/42.md) - Discusses system version evolution strategies
  - Backward compatibility guarantees
  - Gradual updates
  - Feature toggle mechanisms
- [Rule Structure Optimization and Simplification](English_Internship_Logs/45.md) - Demonstrates data structure evolution management
  - Architecture refactoring planning
  - Migration strategies
  - Transitional dual-system operation
- [Rule Model Design Based on Pydantic](English_Internship_Logs/44.md) - Introduces data model version management
  - Model version control
  - Field deprecation strategies
  - Default value evolution 