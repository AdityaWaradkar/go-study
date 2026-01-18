## **PHASE 1: GO LANGUAGE FOUNDATIONS**

### **Chapter 1: Introduction to Go**

**1.1** What problems Go was designed to solve\
**1.2** Go design principles (simplicity, concurrency, tooling)\
**1.3** Go vs other backend languages (conceptual comparison)\
**1.4** Where Go is used in backend and infrastructure\
**1.5** Installing Go and verifying installation\
**1.6** Understanding the Go toolchain\
**1.7** `go run` vs `go build` vs `go install`\
**1.8** Understanding Go binaries and execution model

***

### **Chapter 2: Program Structure and Packages**

**2.1** Anatomy of a minimal Go program\
**2.2** The `package` keyword and its role\
**2.3** The `main` package and `main()` function\
**2.4** Import statements and import paths\
**2.5** Exported vs unexported identifiers\
**2.6** File organization inside a package\
**2.7** How Go finds and builds packages

***

### **Chapter 3: Variables and Constants**

**3.1** Variable declaration using `var`\
**3.2** Short variable declaration (`:=`)\
**3.3** Type inference rules\
**3.4** Explicit type declarations\
**3.5** Zero values and default initialization\
**3.6** Constant declaration and immutability\
**3.7** Typed vs untyped constants\
**3.8** Scope of variables

***

### **Chapter 4: Control Flow**

**4.1** Boolean expressions and conditions\
**4.2** `if` statement structure\
**4.3** `if` with short statements\
**4.4** `for` as the only loop in Go\
**4.5** Traditional loop patterns\
**4.6** Infinite loops and controlled exits\
**4.7** `switch` statement behavior\
**4.8** Expression vs type switches\
**4.9** `break` and `continue` semantics\
**4.10** Understanding execution flow

***

### **Chapter 5: Built-in Data Types**

**5.1** Boolean types\
**5.2** Integer types and size implications\
**5.3** Floating-point types\
**5.4** Strings and immutability\
**5.5** Rune vs byte\
**5.6** Arrays and fixed-size behavior\
**5.7** Slices and dynamic sizing\
**5.8** Slice internals (length vs capacity)\
**5.9** Slice copying and sharing\
**5.10** Maps and key-value storage\
**5.11** Map initialization and access rules

***

### **Chapter 6: Structs and Data Modeling**

**6.1** Defining structs\
**6.2** Struct field types and tags\
**6.3** Struct initialization patterns\
**6.4** Zero values in structs\
**6.5** Nested structs\
**6.6** Anonymous struct fields\
**6.7** Structs as value types\
**6.8** When to use pointers to structs

***

### **Chapter 7: Functions**

**7.1** Function declaration syntax\
**7.2** Function parameters and arguments\
**7.3** Return values\
**7.4** Multiple return values\
**7.5** Named return values\
**7.6** Variadic functions\
**7.7** Anonymous functions\
**7.8** Closures and captured variables

***

### **Chapter 8: Error Handling**

**8.1** Errors as values\
**8.2** Creating errors\
**8.3** Returning and propagating errors\
**8.4** Error wrapping\
**8.5** Inspecting wrapped errors\
**8.6** Sentinel errors vs typed errors\
**8.7** When to use `panic`\
**8.8** Recovering from panics\
**8.9** Defining error boundaries

***

### **Chapter 9: Interfaces**

**9.1** What interfaces represent in Go\
**9.2** Interface declaration syntax\
**9.3** Implicit interface implementation\
**9.4** Interface satisfaction rules\
**9.5** Empty interface and its use cases\
**9.6** Designing small interfaces\
**9.7** Dependency inversion with interfaces\
**9.8** Interface-based testing

***

### **Chapter 10: Methods and Composition**

**10.1** Defining methods\
**10.2** Value receivers\
**10.3** Pointer receivers\
**10.4** Method sets\
**10.5** Embedding structs\
**10.6** Composition over inheritance\
**10.7** Designing behavior with composition

***

### **Chapter 11: Concurrency Basics**

**11.1** What concurrency means in Go\
**11.2** Goroutines and lightweight execution\
**11.3** Goroutine lifecycle\
**11.4** Channel creation\
**11.5** Sending and receiving on channels\
**11.6** Buffered channels\
**11.7** Channel blocking behavior\
**11.8** Closing channels\
**11.9** The `select` statement\
**11.10** Synchronization using `sync` primitives

<br>
<br>

## **PHASE 2: RUNTIME, MEMORY, AND QUALITY**

### **Chapter 12: Go Runtime and Memory**

**12.1** Stack vs heap\
**12.2** Escape analysis (conceptual)\
**12.3** Garbage collection basics\
**12.4** Allocation costs\
**12.5** Object lifetime\
**12.6** Program initialization order\
**12.7** `init()` functions

***

### **Chapter 13: Testing and Debugging**

**13.1** Go testing philosophy\
**13.2** Writing basic unit tests\
**13.3** Table-driven tests\
**13.4** Testing error cases\
**13.5** Testing concurrent code\
**13.6** Benchmarks\
**13.7** Profiling CPU usage\
**13.8** Profiling memory usage\
**13.9** Debugging Go programs

<br>
<br>

## **PHASE 3: BACKEND ENGINEERING WITH GO**

### **Chapter 14: Web and HTTP Fundamentals**

**14.1** Client-server model\
**14.2** HTTP request structure\
**14.3** HTTP response structure\
**14.4** HTTP methods and semantics\
**14.5** Status codes and meaning\
**14.6** Headers and metadata\
**14.7** Go HTTP server lifecycle

***

### **Chapter 15: Building HTTP Services in Go**

**15.1** Using `net/http`\
**15.2** Handlers and handler functions\
**15.3** Routing basics\
**15.4** Middleware concept\
**15.5** Request parsing\
**15.6** JSON encoding and decoding\
**15.7** Error handling in HTTP services\
**15.8** Context propagation\
**15.9** Timeouts and cancellations

***

### **Chapter 16: Authentication and Authorization**

**16.1** Authentication vs authorization\
**16.2** Password hashing\
**16.3** Token-based authentication\
**16.4** JWT structure and validation\
**16.5** Authorization checks\
**16.6** RBAC design\
**16.7** Rate limiting concepts

***

### **Chapter 17: Database Integration**

**17.1** SQL fundamentals for Go\
**17.2** Using `database/sql`\
**17.3** Query execution\
**17.4** Scanning results\
**17.5** Prepared statements\
**17.6** Transactions\
**17.7** Connection pooling\
**17.8** Handling database errors

<br>
<br>

## **PHASE 4: SYSTEM DESIGN**

### **Chapter 18: Backend Architecture**

**18.1** Monolith vs modular monolith\
**18.2** Service boundaries\
**18.3** REST vs gRPC\
**18.4** Idempotency\
**18.5** Retries and failures\
**18.6** Graceful shutdown

<br>
<br>

## **PHASE 5: DEVOPS FOR GO ENGINEERS**

### **Chapter 19: Linux and OS Basics**

**19.1** Processes and signals\
**19.2** Environment variables\
**19.3** Files and file descriptors\
**19.4** Networking basics

***

### **Chapter 20: Containerization**

**20.1** Docker fundamentals\
**20.2** Dockerfile structure\
**20.3** Building Go images\
**20.4** Multi-stage builds\
**20.5** Container networking

***

### **Chapter 21: CI/CD and Deployment**

**21.1** Build pipelines\
**21.2** Automated testing in CI\
**21.3** Deployment strategies\
**21.4** Secrets management

***

### **Chapter 22: Kubernetes Fundamentals**

**22.1** Kubernetes architecture\
**22.2** Pods and containers\
**22.3** Services\
**22.4** Deployments\
**22.5** ConfigMaps and Secrets\
**22.6** Health checks\
**22.7** Scaling and rolling updates

<br>
<br>

## **PHASE 6: OBSERVABILITY AND RELIABILITY**

### **Chapter 23: Observability**

**23.1** Structured logging\
**23.2** Metrics fundamentals\
**23.3** Prometheus basics\
**23.4** Grafana dashboards\
**23.5** Alerting principles

***

### **Chapter 24: Security and Reliability**

**24.1** Secure coding practices\
**24.2** Input validation\
**24.3** Preventing common attacks\
**24.4** Timeouts and circuit breakers\
**24.5** Fault tolerance mindset

<br>
<br>

## **PHASE 7: REAL-WORLD PRACTICE**

### **Chapter 25: Production-Grade Projects**

**25.1** REST API project\
**25.2** Concurrent worker system\
**25.3** gRPC internal service\
**25.4** Observability-enabled service\
**25.5** Full deployment pipeline

***
