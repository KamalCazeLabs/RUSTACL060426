<div align="center">
  <img src="https://www.rust-lang.org/logos/rust-logo-512x512.png" width="120" alt="Rust Logo" />
  <h1>🦀 Rust Programming – 24 Hours Intensive Course</h1>
  <p><strong>Transition from C/C++ to Rust and develop real-world system-level applications.</strong></p>

  <p>
    <img src="https://img.shields.io/badge/Trainer-Kamal%20Kumar%20Mukiri-orange?style=for-the-badge&logo=teacher" alt="Trainer" />
    <img src="https://img.shields.io/badge/Organization-Apt%20Computing%20Labs-blue?style=for-the-badge&logo=organization" alt="Org" />
    <img src="https://img.shields.io/badge/Mode-Live%20via%20Zoom%20+%20Recorded-green?style=for-the-badge&logo=zoom" alt="Mode" />
  </p>
  <p>
    <img src="https://img.shields.io/badge/Duration-24%20Hours-brightgreen?style=flat-square" alt="Duration" />
    <img src="https://img.shields.io/badge/Schedule-Mon%20to%20Thu%20(Starting%20April%206)-yellow?style=flat-square" alt="Schedule" />
    <img src="https://img.shields.io/badge/Time-8:00pm%20to%209:30pm%20(IST)-purple?style=flat-square" alt="Time" />
  </p>
  <p>
    <img src="https://img.shields.io/badge/Fee-₹6000%20+%20GST%20%7C%20₹4000%20+%20GST%20(Students)-red?style=flat-square" alt="Fee" />
    <a href="mailto:kamal@aptcomputinglabs.com"><img src="https://img.shields.io/badge/Contact-kamal@aptcomputinglabs.com-blue?style=flat-square&logo=minutemailer" alt="Email" /></a>
  </p>
</div>

---

## 🎯 Course Objective

> 📖 **Current Students:** Jump straight to the **[Daily Session Logs & Resources (daily.md)](./daily.md)** for session recordings, PPTs, MCQs, and assignments!

This intensive course is meticulously designed to help participants:
- 🏗️ **Build a strong foundation** in Rust programming from the ground up.
- 🧠 **Understand core paradigms**: memory safety, ownership, and concurrency without data races.
- 🔄 **Transition seamlessly** from C/C++ to Rust, adopting a modern system programming mindset.
- 🚀 **Develop real-world** system-level applications and utilities.

## 👨‍💻 Target Audience

- **C / C++ Developers** (especially those in embedded/system domains).
- **Software Engineers** preparing for modern systems programming roles.
- **Students & Enthusiasts** interested in Rust, Web3, or high-performance, safe systems.

---

## 📌 Pre-Requisites

<div class="row">

| 🔴 **Mandatory** | 🟡 **Recommended** | 🟢 **Optional (Good to Have)** |
|:---|:---|:---|
| Basic programming knowledge (C/C++ highly preferred). | Linux basics (commands, file system navigation). | Exposure to system programming concepts. |
| Understanding of Variables, Loops, Functions. | Basic compilation concepts (e.g., `gcc`, `make`). | Understanding of memory management strategies in C/C++. |
| Understanding of Pointers (crucial for grasping Rust's ownership model). | | |

</div>

---

## 🗓️ Course Structure (24 Hours Plan)

All code and projects will be available in the [`modules/`](./modules) directory of this repository as the course progresses.

<details>
<summary><b>🔹 Module 1: Introduction to Rust (2 Hours)</b></summary>

- Why Rust? Industry use cases and adoption.
- Rust vs C/C++: Paradigms and trade-offs.
- Toolchain setup (`rustup`, `cargo`, `rustc`).
- Writing and dissecting your first program.

👉 **Intro Project:** <code><a href="./modules/01_intro_to_rust/hello_rust">hello_rust</a></code>
</details>

<details>
<summary><b>🔹 Module 2: Ownership & Borrowing ⭐ Core (4 Hours)</b></summary>

- Ownership rules and the borrow checker.
- Move semantics vs Copy semantics.
- Borrowing & strict referencing rules.
- Mutable vs immutable borrowing safely.
- Introduction to Lifetimes.

👉 **Tiny Exercise:** Rewrite C-style memory management code in Rust ([Source Code](./modules/02_ownership_and_borrowing/exercise_c_to_rust)).

</details>

<details>
<summary><b>🔹 Module 3: Data Types & Control Flow (3 Hours)</b></summary>

- Primitive types, compounds, and slices.
- Structs & Enums (and how they differ from C).
- Advanced pattern matching with `match`.
- Demystifying `Option` & `Result` types.

👉 **Assignment:** Build a CLI-based calculator ([Source Code](./modules/03_data_types_control_flow/cli_calculator_assignment)).

</details>

<details>
<summary><b>🔹 Module 4: Collections & Error Handling (3 Hours)</b></summary>

- Deep dive into Vectors and HashMaps.
- Strings in Rust (`String` vs `&str`).
- Robust error handling strategies:
  - `Result` enum
  - `panic!` macro
  - `unwrap` vs `expect` and best practices.

👉 **Examples:** <code><a href="./modules/04_collections_error_handling/code_examples">code_examples</a></code>
</details>

<details>
<summary><b>🔹 Module 5: Modules, Crates & Cargo (2 Hours)</b></summary>

- Structuring a large Rust project.
- Modules, paths, and visibility (`pub`).
- Managing external dependencies (crates).
- Optimizing Cargo workflows and workspaces.

👉 **Example:** <code><a href="./modules/05_modules_crates_cargo/workspace_example">workspace_example</a></code>
</details>

<details>
<summary><b>🔹 Module 6: Traits & Generics (3 Hours)</b></summary>

- Understanding Traits (similar to interfaces but more powerful).
- Utilizing Generics for DRY code.
- Applying Trait bounds.
- Real-world abstraction patterns in Rust.

👉 **Examples:** <code><a href="./modules/06_traits_generics/code_examples">code_examples</a></code>
</details>

<details>
<summary><b>🔹 Module 7: Concurrency in Rust (3 Hours)</b></summary>

- Fearless Concurrency: Threads in Rust.
- Message passing using Channels (`mpsc`).
- Shared state safely: `Mutex` & `Arc`.
- How Rust prevents Data Races at compile time.

👉 **Tiny Project:** Multi-threaded log processor ([Source Code](./modules/07_concurrency/multi_threaded_log_processor)).

</details>

<details>
<summary><b>🔹 Module 8: System Programming Concepts 🔥 (3 Hours)</b></summary>

- Efficient file handling.
- Spawning and managing external processes.
- OS interaction and environment variables.
- Building robust CLI tools in Rust (`clap` crate intro).

👉 **Tiny Project:** Build a mini system monitor (CPU / file watcher) ([Source Code](./modules/08_system_programming/mini_system_monitor)).

</details>

<details>
<summary><b>🔹 Module 9: Final Project + Wrap-up (1 Hour)</b></summary>

- Combining all concepts into a final unified tool.
- Building a complete CLI tool or mini system utility ([Source Code](./modules/09_final_project/system_utility)).
- Best practices in the Rust ecosystem.
- Next steps and Interview preparation guidance.
</details>

---

## 📦 Deliverables & Evaluation

| Deliverables | Evaluation Metrics |
| :--- | :--- |
| ✅ Well-structured PPTs *(Available in LMS / during sessions)* | 📊 MCQs after every module to test retention |
| ✅ High-quality Recorded sessions | 📝 Assignment submissions and code reviews |
| ✅ Module-specific MCQs & Quizzes | 🏆 Final project evaluation and feedback |
| ✅ Hands-on Assignments & Tiny Projects | |
| ✅ A complete end-to-end Final Mini Project | |
| ✅ This **GitHub-ready codebase** for your portfolio | |

---

## 🚀 Tools & Environment

To get the most out of this course, ensure your local development environment has:
- **Rust Toolchain:** Stable release (via `rustup`).
- **Package Manager:** `cargo` (comes with rustup).
- **IDE Recommendations:** `VS Code` (with `rust-analyzer` extension) or `CLion` (with Rust plugin).
- **Operating System:** Linux or macOS is preferred for system programming exercises.

## 💡 Unique Value Proposition

- 🛠️ **Systems Mindset:** Focused entirely on a system programming mindset rather than just basic syntax.
- 🌉 **Perfect for C/C++ Devs:** Specially tailored for engineers transitioning from C or C++, relating Rust’s paradigms to known C/C++ memory models.
- 🏭 **Real-World Patterns:** Covers industry-standard patterns for structuring code, error handling, and robust concurrency.
- 🧪 **Highly Interactive:** Heavily hands-on with architecture thinking rather than passive learning.

<br>

<div align="center">
  <i>Empowering the next generation of systems programmers with safe, concurrent, and blazing-fast code.</i>
</div>
