# Interactive Modular Lifting Rings

An advanced mathematical visualization tool for exploring modular arithmetic patterns, prime gaps, and lifting relationships in the context of **M_n = 30 × 2^n**.
https://wessengetachew.github.io/Primes/

## 🎯 Overview

This interactive visualization explores the mathematical framework of **modular twin lifting rings** and generalized gaps, providing insights into:

- **Euler's totient function** φ(M_n) for moduli M_n = 30 × 2^n
- **Prime gap patterns** (twin primes, cousin primes, sexy primes, and beyond)
- **Lifting relationships** between different modular levels
- **Residue distributions** and their geometric properties

## 🚀 Features

### Core Mathematical Features
- **16 modular levels**: n ∈ {-5, -4, -3, -2, -1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
- **Custom gap analysis**: Generate even gaps from 2 to 100+
- **Two lift types**:
  - Direct lifts: r → r (same residue across rings)
  - Modular lifts: r → r + M×2^n (shifted by modulus difference)

### Interactive Visualization
- **Nested ring display** with configurable nesting order
- **Color-coded gap connections** with unique hues per gap type
- **Real-time parameter adjustment** (zoom, rotation, selection)
- **Smooth animations** with 60fps performance optimization

### Advanced Controls
- **Multi-gap selection**: Visualize multiple gap types simultaneously
- **Ring filtering**: Choose any combination of modular levels
- **Export functionality**: High-quality JPEG/PNG export with metadata
- **Responsive design**: Works on desktop, tablet, and mobile devices

## 📊 Mathematical Background

### Modular Framework
The visualization is based on the modular sequence:
```
M_n = 30 × 2^n
```

Where:
- **n = 0**: M₀ = 30 (base Euler residue system)
- **n > 0**: Expanding moduli (60, 120, 240, ...)
- **n < 0**: Fractional moduli (15, 7.5, 3.75, ...)

### Euler's Totient Function
For each modulus M_n, we calculate:
```
φ(M_n) = |{r : 1 ≤ r ≤ M_n, gcd(r, M_n) = 1}|
```

### Gap Analysis
Valid transitions are pairs (r, r+g) where both residues are coprime to the modulus:
- **Gap 2**: Twin primes (11,13), (17,19), (29,31)
- **Gap 4**: Cousin primes (1,5), (7,11), (13,17)
- **Gap 6**: Sexy primes (5,11), (7,13), (17,23)
- **Gap 2n**: Any even gap following the same pattern

### Lifting Rules
The framework establishes lifting relationships between levels:
1. **Direct Lifting**: If (r, r+g) ∈ φ(M_n), then (r, r+g) ∈ φ(M_{n+1})
2. **Modular Lifting**: Residues can also lift with modular shifts

## 🛠️ Usage

### Basic Operation
1. **Select rings**: Choose which modular levels (n values) to display
2. **Choose gaps**: Select gap sizes to visualize (2, 4, 6, 8, ...)
3. **Configure display**: Adjust zoom, rotation, labels, and lift lines
4. **Export results**: Save high-quality images for research or presentation

### Advanced Features
- **Custom gap ranges**: Generate all even gaps up to any limit
- **Lift line analysis**: Compare direct vs. modular lifting patterns
- **Animation mode**: Smooth rotation for dynamic presentations
- **Invert nesting**: Reverse ring order for structural comparison

### Export Options
- **📷 JPEG Export**: High-resolution with solid background
- **🖼️ PNG Export**: Transparent background, perfect for presentations
- **Metadata inclusion**: Automatically includes configuration details

## 🎨 Visual Elements

### Color Coding
- **Residue points**: HSL color distribution based on angular position
- **Gap connections**: Unique hues for each gap type
- **Lift lines**: 
  - Gold solid lines for direct lifts (r → r)
  - Red dashed lines for modular lifts (r → r + M×2^n)
- **Ring boundaries**: Subtle white circles

### Interactive Elements
- **Hover effects**: Enhanced visual feedback
- **Real-time updates**: Instant visualization changes
- **Smooth animations**: Optional rotation with performance optimization
- **Responsive scaling**: Automatic adjustment for different screen sizes

## 🔬 Research Applications

### Prime Number Theory
- **Gap distribution analysis**: Study patterns in prime spacing
- **Infinite chains**: Explore how gaps propagate across modular levels
- **Sieve theory**: Visualize sieve patterns in arithmetic progressions

### Modular Arithmetic
- **Residue systems**: Understand coprime distributions
- **Lifting phenomena**: Study how structures preserve across scales
- **Symmetry analysis**: Explore rotational and reflective symmetries

### Educational Use
- **Visual learning**: Intuitive understanding of abstract concepts
- **Interactive exploration**: Hands-on mathematical discovery
- **Research presentation**: Professional-quality visualizations

## 📱 Technical Specifications

### Browser Compatibility
- **Modern browsers**: Chrome, Firefox, Safari, Edge
- **Canvas support**: HTML5 Canvas with 2D context
- **Responsive design**: CSS Grid and Flexbox layouts
- **Performance**: Optimized for 60fps animations

### Mathematical Accuracy
- **Precise calculations**: Exact GCD computations
- **Floating-point handling**: Robust arithmetic for fractional moduli
- **Angle calculations**: Accurate 2πr/M positioning
- **Color distribution**: Even HSL space allocation

### Export Quality
- **High resolution**: 2x scaling for crisp images
- **Format options**: JPEG (solid background) and PNG (transparent)
- **Metadata**: Configuration details embedded in export
- **File naming**: Automatic timestamp-based naming

## 🚀 Getting Started

### Quick Start
1. **Clone or download** the repository
2. **Open** `index.html` in a modern web browser
3. **Explore** the default configuration (n = 0,1,2 with Gap 2)
4. **Experiment** with different ring and gap combinations

### Recommended Explorations
1. **Twin Prime Chains**: Start with Gap 2, rings n = 0,1,2,3
2. **Multi-Gap Analysis**: Enable gaps 2,4,6 simultaneously
3. **Lifting Comparison**: Toggle direct vs. modular lift lines
4. **Scale Exploration**: Include negative n values for fractional moduli

## 📖 Mathematical References

### Foundational Concepts
- **Euler's Totient Function**: φ(n) and its multiplicative properties
- **Modular Arithmetic**: Residue systems and coprimality
- **Prime Gap Theory**: Twin primes, cousin primes, sexy primes

### Advanced Topics
- **Sieve Theory**: Patterns in arithmetic progressions
- **Lifting Phenomena**: Structure preservation across scales
- **Modular Forms**: Connections to number-theoretic functions

## 🤝 Contributing

### Code Contributions
- **Bug reports**: Use GitHub issues for bug tracking
- **Feature requests**: Suggest mathematical enhancements
- **Performance improvements**: Optimize rendering or calculations
- **Documentation**: Improve mathematical explanations

### Mathematical Extensions
- **New gap types**: Extend to odd gaps or other patterns
- **Alternative moduli**: Explore different base sequences
- **Theoretical connections**: Link to other mathematical structures

## 📄 License

This project is released under the **MIT License**, allowing for both academic and commercial use with attribution.

## 🙏 Acknowledgments

- **Number Theory Community**: For foundational research on prime gaps
- **Mathematical Visualization**: Inspired by geometric number theory
- **Open Source**: Built with standard web technologies

## 📞 Contact

- **Issues**: GitHub Issues for bug reports and feature requests
- **Discussions**: GitHub Discussions for mathematical questions
- **Research**: For academic collaboration and research applications

---

**Explore the infinite patterns of modular arithmetic through interactive visualization!**

*Created with ❤️ for the mathematical community*
