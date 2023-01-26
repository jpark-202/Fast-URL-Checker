<h1>LinkVerify</h1>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">🧐 Project philosophy</a>
    </li>
    <li>
      <a href="#getting-started">🏃 Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">👨‍💻 Usage</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## 🧐 Project philosophy
The motivation is mainly on learning GO and goroutines 

Fast-URL-Checker, as indicated by the name, it is a _quick_ url checking application. It uses "goroutines" to thrive in concurrency (speed).

## 🏃 Getting Started
### Prerequisites

* Golang <br/>
  * Download link: https://go.dev/doc/install

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/jpark-202/Fast-URL-Checker.git
   ```
2. Enter your URLs in `main()`
   ```go
    urls := []string{
		"ENTER YOUR URL 1",
		"ENTER YOUR URL 2",
                .
                .
                .
		"ENTER YOUR URL n-1",
		"ENTER YOUR URL n",
	}

   ```
3. Execute to verify the URLs!
    ```sh
    go run fastURLChecker.go
    ```
<!-- USAGE EXAMPLES -->
## 👨‍💻 Usage (How it is be used)
Fast-URL-Checker validates any quantity of any form of URL.

1. Input any form and any number of URLs in array.

    ![alt text](https://github.com/jpark-202/Fast-URL-Checker/blob/main/img/img2.png?raw=true)

2. Execute the program
    ```sh
    go run fastURLChecker.go
    ```
    ![alt text](https://github.com/jpark-202/Fast-URL-Checker/blob/main/img/img1.png?raw=true)
