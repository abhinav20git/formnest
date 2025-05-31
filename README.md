# FormNest

FormNest is a visual form builder built with React Remix and Tailwind CSS. It empowers users to create customizable, responsive, and multi-step forms using a drag-and-drop interface. Features include real-time previews, field validations, template saving/loading, and shareable form links.

## ✨ Features

### 🧹 Drag-and-Drop Builder

* Visually add and arrange form fields with an intuitive drag-and-drop interface.
* Supported fields:

  * Text Input
  * Textarea
  * Dropdown
  * Checkbox
  * Date Picker

### 🛠️ Field Configuration

* Configure each field with:

  * Label
  * Placeholder
  * Required toggle
  * Help text
  * Field-specific options (e.g., dropdown values)
  * Validation rules: min/max length, regex (email, phone)

### 📱 Responsive Real-Time Preview

* Live form preview updates as you build
* Built-in validation feedback
* Switch preview mode:

  * Desktop
  * Tablet
  * Mobile

### 📝 Form Templates

* Load predefined form templates (e.g., Contact Us)
* Save custom form templates
* Supports localStorage or API integration

### 🧯 Multi-Step Forms

* Divide forms into multiple steps
* Validate per step with navigation control
* Visual progress indicator across steps

### 🔗 Shareable Forms

* Generate a shareable Form ID on creation
* Public “Form Filler” view for others to access and fill the form
* Load form by ID using URL or localStorage

### 🧠 Bonus Features

* Auto-save builder progress
* Accessible form elements
* Export form schema or JSON

## 🛠️ Tech Stack

* React Remix
* Tailwind CSS
* Zustand (for state management)
* LocalStorage (or custom backend support)

## 🚀 Getting Started

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/formnest.git
   cd formnest
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

## 🔪 Development Notes

* Easily extend field types and validations in the config.
* Backend integration can be added for persistent storage.
* Export logic supports JSON output; consider integrating CSV/PDF in future releases.

## 📆 Folder Structure

* /components: Drag/drop components, form fields
* /routes: Remix routes including builder and public view
* /lib: Utilities and localStorage logic
* /styles: Tailwind setup

## 📸 Screenshots (optional)

Add form builder and preview mode screenshots here.

## 📄 License

MIT License — free to use, modify, and distribute.
