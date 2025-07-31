# 📋 Portfolio Project Customization Checklist

## ✅ **Phase 1: Template Preparation - COMPLETED**
- [x] Cleaned up project-1.html template
- [x] Removed hard-coded inline styles
- [x] Made CSS modular and reusable
- [x] Created consistent class structure
- [x] Added responsive design elements

## ✅ **Phase 2: Project Pages Created - COMPLETED**
- [x] project-1.html (HMPPS Policy Advisory - fully customized)
- [x] project-2.html (A3020 Impact Report - fully customized)
- [x] project-3.html (Volunteer Events Manager - fully customized)
- [x] project-4.html (Product Searching Kiosk - fully customized)

## 📝 **Customization Checklist for Each Project Page**

### **🔧 Required Updates for Each Project**

#### **1. Page Metadata**
- [ ] **Title tag:** Update `<title>Project X - Portfolio</title>`
- [ ] **Page heading:** Update `<h1>Project Name</h1>`
- [ ] **Organization:** Update `<em>Organization Name</em>`
- [ ] **Date:** Update project date
- [ ] **Breadcrumb:** Update `<li class="current">Project Name</li>`

#### **2. Content Section**
- [ ] **Description:** Replace placeholder text with actual project description
- [ ] **Testimonial:** Add real testimonial text (if available)
- [ ] **Attribution:** Update client/organization name
- [ ] **Remove testimonial:** If no testimonial, remove the entire testimonial block

#### **3. Images**
- [ ] **Image file:** Add project image to `/assets/img/portfolio/`
- [ ] **Image path:** Update `src="../assets/img/portfolio/project-image.jpg"`
- [ ] **Alt text:** Update `alt="Project Name"`
- [ ] **Image optimization:** Ensure image is compressed and web-ready

#### **4. Navigation Links**
- [ ] **Portfolio dropdown:** All pages already have correct navigation
- [ ] **Breadcrumbs:** Update breadcrumb text for each project
- [ ] **Internal links:** Verify all relative paths work correctly

---

## 🎯 **Example Customization for Project 2**

### **Before (Template):**
```html
<title>Project 2 - Portfolio</title>
<h1 class="mb-2 mb-lg-0">Project 2</h1>
<div><em>Project Organization</em></div>
<div>Date</div>
<li class="current">Project 2</li>
```

### **After (Customized):**
```html
<title>Fringe Paper - Portfolio</title>
<h1 class="mb-2 mb-lg-0">Fringe Paper</h1>
<div><em>University of Sussex</em></div>
<div>December 2024</div>
<li class="current">Fringe Paper</li>
```

---

## 📁 **File Structure**
```
portfolio/
├── project-1.html (HMPPS Policy Advisory - ✅ Complete)
├── project-2.html (A3020 Impact Report - ✅ Complete)
├── project-3.html (Volunteer Events Manager - ✅ Complete)
└── project-4.html (Product Searching Kiosk - ✅ Complete)

assets/img/portfolio/
├── HMPPS_prison.jpg (✅ Complete)
├── isle_of_wight.jpg (✅ Complete)
├── product_kiosk.jpg (✅ Complete)
└── fringe_paper.jpeg (✅ Complete - in Caine folder)
```

---

## 🎨 **Template Features**

### **✅ Consistent Styling**
- Two-column layout (8/4 split on desktop)
- Sticky image on right side
- Responsive design (stacks on mobile)
- Quote icons with proper styling
- AOS animations for smooth transitions

### **✅ Reusable Components**
- `.project-image-container` - Sticky image wrapper
- `.testimonial-item` - Testimonial styling
- `.quote-icon-left/right` - Quote mark styling
- `.testimonial-attribution` - Attribution styling

### **✅ Best Practices**
- Semantic HTML structure
- Accessible alt text for images
- Proper heading hierarchy
- Mobile-first responsive design
- Clean, maintainable CSS

---

## 🚀 **Next Steps**

1. **Add project images** to `/assets/img/portfolio/`
2. **Customize each project page** using the checklist above
3. **Test all pages** in browser for responsiveness
4. **Update main portfolio section** in index.html if needed
5. **Optimize images** for web performance

---

## 📞 **Support**

If you need help customizing any specific project page, refer to this checklist and the example customizations above. Each project page follows the same structure, making it easy to maintain consistency across your portfolio. 