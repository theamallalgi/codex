![HEADER IMAGE](https://github.com/theamallalgi/codex/blob/main/dependencies/header.png?raw=true)

# The Component Codex 📜

The **Component Codex**, a structured and systematic approach to organizing and categorizing tangible and intangible components, objects, and tools. This project aims to standardize the classification of physical and digital assets to make them easier to identify, track, and reference using a unified code structure.

## **Table of Contents**
1. [Overview](#overview)
2. [Classification System](#classification-system)
    - [Hierarchy Structure](#hierarchy-structure)
3. [Code Syntax](#code-syntax)
4. [Code Generation Rules](#code-generation-rules)
5. [Examples](#examples)
6. [Special Cases](#special-cases)

## **Overview**

The **Component Codex** aims to provide a structured framework to classify physical and digital items. Each item is classified under a set of predefined categories, which allows for easy identification and organization. The codification system assigns unique 3-digit serial numbers to each item, ensuring a standard format across different types of components.

## **Classification System**

The classification system is divided into several **hierarchies** and **categories**. These hierarchies help define the specific attributes of an item based on its nature (tangible or intangible), usage, and accessibility.

### **Hierarchy Structure**

1. **Q1: Primary Classification**  
   - **TN** – Tangible (Physical items)  
   - **IN** – Intangible (Non-physical items, digital, conceptual)

2. **Q2: Functional Category (Physical State / Usage Type)**  
   - **For Tangible (TN):**
     - **PR** – Portable (Items that can be carried or moved easily)  
     - **FX** – Fixed (Stationary, immobile items)
   
   - **For Intangible (IN):**
     - **CL** – Cloud-Based (Stored or hosted online)  
     - **DS** – Local Storage (Stored locally, offline)

3. **Q3: Resource Type**  
   - **For Tangible (TN)**:
     - **FL** – Fueled (Items requiring fuel or energy)  
     - **NF** – Non-Fueled (Items that do not require fuel or energy)  
     - **RS** – Reusable (Items that can be reused multiple times)  
     - **CN** – Consumable (Items used up after a single use)  
     - **FN** – Fun (Items used for entertainment or leisure)

   - **For Intangible (IN)**:
     - **DEV** – Development (Tools, platforms for coding, debugging)  
     - **DES** – Design (Creative tools for visuals, graphics, UX/UI)  
     - **DOC** – Documentation (Files, repositories for knowledge and manuals)  
     - **EDU** – Education (eBooks, courses, learning tools)  
     - **MED** – Media (Audio, video, images, media files)

4. **Q4: Accessibility/Ownership**  
   - **PN** – Personal (Items owned by an individual)  
   - **PS** – Public (Items shared or available to multiple users)  
   - **PNW/PSW** – Work or Product-Made (Items created for others or as a product for public consumption)

## **Code Syntax**

Each item is assigned a unique code based on the classification hierarchy. The code is structured as follows:

```scss
[H1][H2][H3][...](NAME)[SLNO]
```

- **[H1]** – Primary Classification (TN for Tangible, IN for Intangible)  
- **[H2]** – Functional Category (PR for Portable, FX for Fixed, CL for Cloud, DS for Local)  
- **[H3]** – Resource Type (FL for Fueled, NF for Non-Fueled, DEV for Development, etc.)
- **[...]** - More Classes if needed
- **(NAME)** – A shortened name or identifier for the item preferably not longer than 3 letters
- **[SLNO]** – A unique 3-digit serial number starting from [001]

## **Code Generation Rules**

1. **Serial Numbering**:  
   The serial numbers are always 3 digits long, starting from **[001]**.  
   - **Mother Component**: The first entry for each category is assigned the serial number **[000]** to represent the "Mother Component" or the primary example in that classification.

2. **Example Structure**:
   - The first item in any category should have **[000]** as its serial number. This denotes the "Mother Component", the head of all other components in the same classification.

3. **Code Format**:  
   - The codes always follow the pattern `[H1][H2][H3](NAME)[SLNO]`, ensuring consistency across all items.
   - Use **3-letter abbreviations** for the item’s name.

## **Examples**

### **Example 1: Portable Laptop**  
- **Primary Classification**: Tangible (TN)  
- **Functional Category**: Portable (PR)  
- **Resource Type**: Non-Fueled (NF)  
- **Accessibility**: Personal (PN)  
- **Name**: Laptop  
- **Serial Number**: [001]

**Code**: `TNPRNFPN(LPT)[001]`

### **Example 2: Cloud-Based Design File**  
- **Primary Classification**: Intangible (IN)  
- **Functional Category**: Cloud-Based (CL)  
- **Resource Type**: Design (DES)  
- **Accessibility**: Public (PS)  
- **Name**: Design File  
- **Serial Number**: [002]

**Code**: `INCLPSDES(DSF)[002]`

### **Special Cases:**

- **Mother Component**:  
   Any category's first item will have the serial number **[000]**. This is the "Mother Component" and represents the core, starting item in that classification.  
   - For example, **Tangible Portable Laptop** might be the first instance of a portable item: `TNPRNFPN(LPT)[000]`

## **Conclusion**

The **Component Codex** provides a streamlined and consistent way of categorizing, organizing, and tracking both tangible and intangible items. The hierarchical classification ensures that each item can be described succinctly, while the standardized code syntax allows for easy identification. This system is ideal for any scenario where items need to be cataloged, whether they are physical objects like gadgets or intangible digital assets like files and software.

For more details or questions, feel free to open an issue or contribute to the project!
