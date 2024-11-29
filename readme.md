## **Installation / Reference Material:**

- **[JDK (Java Development Kit)](https://www.oracle.com/java/technologies/downloads/)**  
  _(Ensure you download the latest Long-Term Support (LTS) version, e.g., JDK 21 or above.)_

- **[JRE (Java Runtime Environment)](https://www.oracle.com/java/technologies/javase-jre8-downloads.html)**  
  _(Optional if running compiled Java applications only; not needed if JDK is installed.)_

- **[CloudSim Plus](https://github.com/CloudSimPlus/CloudSimPlus)**  
  _(Recommended over the original CloudSim as it's actively maintained and more feature-rich.)_

- **[Eclipse IDE](https://www.eclipse.org/downloads/)**  
  _(Choose the "Eclipse IDE for Java Developers" package for best compatibility.)_

- **[Source Repository](https://github.com/suyash-more/Cloud-Computing-Projects)**

---

### **Setup Steps:**

1. **Install an IDE:**  
   Recommended: **Eclipse IDE**, or alternatives like **IntelliJ IDEA** or **VS Code** with Java extensions.

2. **Install JDK:**  
   Download and install the latest version of the JDK. Verify installation with:  
   ```bash
   java -version  
   javac -version
   ```

3. **Set Environment Variables (if not auto-configured):**  
   - Open the **System Properties** → **Advanced** → **Environment Variables**.  
   - Under "System variables," select **Path** → **Edit** → Add the JDK `bin` directory. Example:  
     ```plaintext
     C:\Program Files\Eclipse Adoptium\jdk-21.0.0\bin
     ```

4. **Clone the Repository:**  
   Clone the source code from the repository:  
   ```bash
   git clone https://github.com/suyash-more/Cloud-Computing-Projects.git
   ```

5. **Set Up Eclipse Project:**  
   - Open **Eclipse** and create a new **Java Project**.  
   - Name your project and ensure the JDK is correctly selected.

6. **Import Files:**  
   - Inside the **`src`** folder, create a package (e.g., `cloudsim.scheduler`).  
   - Copy and paste all files from the repository's **`Scheduling-Algorithm-in-CloudSim/src`** folder into your package.

7. **Configure Build Path:**  
   - Right-click on the project → **Build Path** → **Configure Build Path**.  
   - Under the **Libraries** tab, click **Add External JARs...**  
   - Navigate to the CloudSim Plus `jar` files (from the `CloudSimPlus` repository) and add them.

8. **Update Package Names (if needed):**  
   - Ensure that package declarations in each file match your project's structure.

9. **Run the Application:**  
   - Right-click on the project → **Run As** → **Java Application**.  
   - Choose the **`SJF_Scheduler.java`** file when prompted.

---
