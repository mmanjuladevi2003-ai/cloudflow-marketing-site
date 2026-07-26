# Prioritized Fix List

## Overview

The following recommendations are prioritized based on expected performance impact and implementation effort.

| Priority | Recommendation | Expected Impact | Implementation Effort |
|----------|----------------|-----------------|-----------------------|
| High | Remove unused JavaScript | Very High | Medium |
| High | Optimize and compress images | High | Low |
| High | Reduce third-party scripts | High | Medium |
| Medium | Improve browser caching | Medium | Low |
| Medium | Minify CSS and JavaScript | Medium | Low |
| Low | Optimize DOM size | Low | Medium |

---

## High Priority

### 1. Remove Unused JavaScript

**Reason**

PageSpeed Insights reports approximately **1.7 MB** of unused JavaScript. Removing unused code will reduce download size and improve page responsiveness.

---

### 2. Optimize Images

**Reason**

Using modern image formats such as **WebP** or **AVIF**, responsive image sizes, and lazy loading will reduce page weight and improve loading performance.

---

### 3. Reduce Third-Party Scripts

**Reason**

Third-party scripts increase loading time and block the browser's main thread. Loading only essential third-party resources improves user experience.

---

## Medium Priority

### 4. Improve Browser Caching

Increase cache lifetimes for static assets so returning visitors do not need to download the same resources repeatedly.

---

### 5. Minify CSS and JavaScript

Minification reduces file size by removing unnecessary spaces, comments, and formatting.

---

## Low Priority

### 6. Optimize DOM Size

Reducing unnecessary HTML elements improves rendering efficiency and reduces browser workload.

---

# Recommendations Not Prioritized

The following optimizations provide relatively small improvements and therefore were not selected as immediate priorities:

- Minor CSS size reductions
- Small JavaScript minification savings
- Minor layout refinements

These should be addressed after the high-impact performance issues are resolved.