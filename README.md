# Mechanical Design Checklist Tool for AutoCAD

This project provides a comprehensive checklist tool for mechanical design tasks using AutoCAD. Developed using Visual Studio, this tool helps streamline the design process by ensuring all necessary steps are completed accurately and timely.

## Checklist Categories and Items

### Machining
- Ensure that the reference point is clearly identified during machining.
- Check if special machining symbols are included (e.g., reamer, threads, magnets, etc.).
- Verify that parts requiring special surface treatment are appropriate in terms of material, performance, and functionality.

### Surface Treatment
- Check if necessary heat treatment details are included.
- Verify the method, type, hardness, depth, material suitability, and cycles for deformation or deterioration related to heat treatment.
- Ensure that the same machining process can be followed.
- Check if the surface treatment symbols and surface roughness symbols are appropriate for functional performance.

### Dimensions
- Ensure that projections are drawn simply so that machinists can understand.
- Check if bolt hole sizes, depths, and quantities match the design specifications.
- Include only minimal necessary dimensions to make it easy to read on-site.

### Assembly
- Reflect critical dimensions required in the design on the part drawings.
- Ensure that necessary information from the design, such as material, surface treatment, and painting, is not omitted.

### Welding
- Check if welding symbols and post-welding finishing symbols are included in welding structures.
- Consider whether special attention is needed for performance and functionality in welding structures.
- Ensure that the welding rod angle is maintained during welding operations.

### Structure
- Check if the shape ensures strength at the adhesive surface and if the part material types are appropriate.
- Verify that it is made symmetrically.

**Loading the Tool in AutoCAD**:
    - Open AutoCAD and load your design file.
    - Use the `NETLOAD` command in the AutoCAD command line to load the compiled .dll file of the checklist tool.
      ```plaintext
      Command: NETLOAD
      ```
    - Navigate to the location of the .dll file, select it, and load it into AutoCAD.

**Running the Checklist Tool**:
    - After loading the .dll file, use the custom command `kenzu` in the AutoCAD command line to start the checklist tool.
      ```plaintext
      Command: kenzu
      ```
    - The tool will guide you through each checklist item, allowing you to verify each aspect of your mechanical design.
    - Follow the on-screen instructions to check each item in your design.

## Contributing

We welcome contributions to improve this project. If you have additional checklist items or suggestions, please leave comments. We are happy to update the checklist based on user feedback.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

By using this tool, mechanical designers can enhance the accuracy and efficiency of their AutoCAD projects, ensuring high-quality outcomes in their work.

---
