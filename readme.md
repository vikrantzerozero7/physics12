# Physics Mind Map - Class 12 Physics Interactive Learning Tool 🎯

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://physics12-uziqxcq849ehzfrxye8z6m.streamlit.app/)

An interactive, bilingual (English/Hindi) mind map application for Class 12 Physics, covering all major chapters from Electric Charges to Semiconductor Electronics. Built with Streamlit and HTML5 Canvas.

## 📚 Live Demo

**App URL:** [https://physics12-uziqxcq849ehzfrxye8z6m.streamlit.app/](https://physics12-uziqxcq849ehzfrxye8z6m.streamlit.app/)

## ✨ Features

### 🌐 Bilingual Support
- Toggle between English and Hindi seamlessly
- All content available in both languages
- Proper Devanagari script support for Hindi

### 🗺️ Interactive Mind Map
- **Hierarchical Structure**: Chapters → Topics → Concepts → Detailed Explanations
- **Visual Navigation**: Color-coded boxes for easy identification
- **Expandable/Collapsible**: Double-click any node to expand/collapse
- **Curved Connections**: Beautiful bezier curves connecting related concepts

### 📖 Comprehensive Content
- **14 Complete Chapters** from Class 12 Physics NCERT
- **50+ Topics** covering all key concepts
- **100+ Concepts** with detailed explanations
- **200+ Formulas** and key points
- Complete with examples and applications

### 🎨 Visual Design
- **Color Scheme**:
  - 🟠 **Physics Title**: Saffron (#FF9933)
  - 🔵 **Chapters**: Blue (#0066CC)
  - 💗 **Topics**: Light Pink (#FFB6C1)
  - 💛 **Concepts**: Light Yellow (#ffe8a3)
  - 💚 **Descriptions**: Light Green (#c7e9c0)
- **Smart Text Wrapping**: Automatically adjusts box sizes based on content
- **Collision Detection**: Prevents overlapping of description boxes

## 📋 Covered Chapters

| Chapter | English Title | Hindi Title |
|---------|--------------|-------------|
| 1 | Electric Charges and Fields | वैद्युत आवेश तथा क्षेत्र |
| 2 | Electrostatic Potential and Capacitance | स्थिरवैद्युत विभव एवं धारिता |
| 3 | Current Electricity | विद्युत धारा |
| 4 | Moving Charges and Magnetism | गतिमान आवेश और चुंबकत्व |
| 5 | Magnetism and Matter | चुंबकत्व एवं द्रव्य |
| 6 | Electromagnetic Induction | वैद्युतचुंबकीय प्रेरण |
| 7 | Alternating Current | प्रत्यावर्ती धारा |
| 8 | Electromagnetic Waves | वैद्युतचुंबकीय तरंगें |
| 9 | Ray Optics and Optical Instruments | किरण प्रकाशिकी एवं प्रकाशिक यंत्र |
| 10 | Wave Optics | तरंग प्रकाशिकी |
| 11 | Dual Nature of Radiation and Matter | विकिरण तथा द्रव्य की द्वैत प्रकृति |
| 12 | Atoms | परमाणु |
| 13 | Nuclei | नाभिक |
| 14 | Semiconductor Electronics | अर्धचालक इलेक्ट्रॉनिकी |

## 🎯 How to Use

1. **Start with PHYSICS Title**:
   - Click on "PHYSICS" to show/hide all content

2. **Explore Chapters**:
   - **Double-click** any chapter to expand/collapse its topics
   - Each chapter has a unique color for easy identification

3. **Dive into Topics**:
   - **Double-click** any topic to see related concepts
   - Topics show article/section numbers for reference

4. **Learn Concepts**:
   - **Double-click** any concept to view detailed explanation
   - Concepts include formulas, properties, and examples

5. **Hide Details**:
   - **Double-click** any description box to hide it
   - Use parent node double-click to collapse entire sections

## 🛠️ Technical Stack

- **Frontend**: HTML5 Canvas, JavaScript
- **Framework**: Streamlit
- **Languages**: Python, JavaScript, HTML/CSS
- **Fonts**: Arial, Noto Sans Devanagari, Nirmala UI
- **State Management**: Custom JavaScript state tracking
- **Rendering**: Dynamic canvas drawing with collision detection

## 🎨 Key Technical Features

### Smart Layout Engine
- **Dynamic Sizing**: Box sizes adjust based on text content
- **Collision Avoidance**: Description boxes automatically reposition to prevent overlap
- **Hierarchical Positioning**: Levels at fixed x-coordinates (Physics → Chapters → Topics → Concepts → Descriptions)

### Interactive Features
- **Event Handling**: Click and double-click detection
- **State Management**: Tracks expansion states for all nodes
- **Visual Feedback**: Collapsed nodes show stacked indicators
- **Curved Connections**: Bezier curves for smooth visual connections

### Performance Optimizations
- **Efficient Rendering**: Only redraws when state changes
- **Memory Management**: Single canvas element with dynamic resizing
- **Responsive Design**: Adapts to different screen sizes

## 📦 Installation (Local Development)

1. Clone the repository:
```bash
git clone https://github.com/yourusername/physics-mindmap.git
cd physics-mindmap
