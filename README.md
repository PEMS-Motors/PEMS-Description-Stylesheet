# CIMCloud CSS Stylesheets

This repository contains CSS files specifically designed for styling pages within the CIMCloud backend used by Precision Electric Motors Sales (PEMS). These stylesheets ensure consistent, clean, and functional design elements across various pages and sections, enhancing the usability and visual presentation of our backend system.

## CSS Files Overview

### `PEMS_ATLDescriptions.css`

The `PEMS_ATLDescriptions.css` file is used for styling the Advanced Technology Layout (ATL) elements in the CIMCloud backend. It includes styles for layout containers, headers, tables, rows, and custom header formats. Key features include:

- **Layout Control**: Styles for main layout containers like `#ATLlayoutcontrol`, `#ATLLeftPanel`, and `#ATLRightPanel` to align elements horizontally and provide a structured layout.
- **Headers and Subheaders**: Custom styles for headers and subheaders to improve readability and section separation.
- **Tables and Rows**: Styling for tables, including cell padding, borders, hover effects, and column-specific text formatting.
- **Interactive Elements**: Hover effects on rows and paragraphs for better user interaction.

### `pemsatl_verX.XXX.css` Series (e.g., `pemsatl_ver0.001.css`, `pemsatl_ver0.002.css`, etc.)

These CSS files represent different versions of the styling specifications for the ATL layout used across various versions of the CIMCloud backend. Each version builds on previous styles, refining and enhancing the layout and appearance of elements. These stylesheets provide compatibility with different versions of the backend.

### `pems2v00.00.XX.css` Series

The `pems2v00.00.XX.css` series contains versioned styles specifically tailored for the PEMS2 layout used in certain pages of the CIMCloud backend. These styles focus on structuring content, providing consistent spacing, and applying color schemes that align with the PEMS branding.

### `pems2-teaser.css`

The `pems2-teaser.css` file provides styles for a teaser layout in the PEMS2 design series. It is a simplified version of the full PEMS2 styles, used for quick previews or minimal content layouts within the CIMCloud backend.

## Usage

All CSS files in this repository are referenced directly by CIMCloud backend pages and should not be modified unless there is a specific need to update the styling across the backend. Each file corresponds to a specific part of the backend or version of the layout, and updates should be done carefully to avoid disrupting the user interface.

### Updating Styles

1. **For Major Changes**: When updating layout styles globally, create a new versioned CSS file (e.g., `pemsatl_ver0.008.css`) and apply changes there. Update backend references as needed.
2. **For Minor Tweaks**: Small adjustments can be made directly in the current version if backward compatibility is maintained. Ensure changes are tested on staging before deploying to production.

## Contributing

If you need to contribute or make modifications, please:
1. Clone this repository.
2. Make changes in the appropriate CSS file, or create a new version file.
3. Test thoroughly on a staging environment within CIMCloud.
4. Submit a pull request or notify the team if changes are approved for production.

---

These CSS files are critical to maintaining a consistent, user-friendly experience on the CIMCloud backend, ensuring that PEMS staff can efficiently navigate and interact with the system. Please handle with care and consult the development team for any significant updates.

---

For questions or further details, please reach out to the PEMS development team.
