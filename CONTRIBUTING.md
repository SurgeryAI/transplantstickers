# Contributing to Transplant Stickers

Thank you for your interest in contributing to the Transplant Stickers project! This sticker pack aims to raise awareness about organ donation and support the transplant community.

## How to Contribute

### Suggesting New Stickers

If you have ideas for new stickers, please open an issue with:
- A description of the sticker concept
- The message or theme it conveys
- How it relates to organ donation or transplant awareness

### Design Guidelines

When creating or proposing stickers, please follow these guidelines:

#### Image Specifications
- **Format**: PNG with transparency
- **Size**: Stickers should be between 300x300 and 618x618 pixels
- **File size**: Keep under 500KB for optimal performance
- **Resolution**: @3x resolution (3x the intended display size)

#### Design Principles
- **Clarity**: Stickers should be clear and recognizable at small sizes
- **Sensitivity**: Be respectful and sensitive when depicting medical themes
- **Consistency**: Match the visual style of existing stickers
- **Accessibility**: Use good color contrast and avoid relying solely on color
- **Cultural sensitivity**: Consider diverse audiences and perspectives

#### Content Guidelines
- Keep stickers positive and encouraging
- Focus on awareness, support, and education
- Avoid graphic medical imagery that might be disturbing
- Respect medical accuracy where applicable
- Include diverse representation when depicting people

### Technical Contributions

#### Adding New Stickers

1. Create your sticker image following the specifications above
2. Add the image to a new folder in `Stickers.xcstickers/Sticker Pack.stickerpack/`
3. Name the folder descriptively (e.g., `heartAwareness.sticker`)
4. Create a `Contents.json` file in the sticker folder:
   ```json
   {
     "info" : {
       "version" : 1,
       "author" : "xcode"
     },
     "properties" : {
       "filename" : "yourSticker.png"
     }
   }
   ```
5. Update `Stickers.xcstickers/Sticker Pack.stickerpack/Contents.json` to include your sticker
6. Test in Xcode to ensure proper display

#### Code Quality
- Test all changes in Xcode before submitting
- Ensure stickers display correctly in both light and dark mode (if applicable)
- Verify stickers work in the Messages app on actual devices

### Naming Conventions

- Use descriptive, meaningful names (e.g., `heartDonor`, `kidneyRecipient`)
- Use camelCase for consistency
- Avoid generic names or auto-generated names
- Keep names concise but clear

### Submitting Changes

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-awareness-sticker`)
3. Make your changes
4. Test thoroughly in Xcode
5. Commit with clear, descriptive messages
6. Push to your fork
7. Open a Pull Request with:
   - Clear description of changes
   - Screenshots of new/modified stickers
   - Explanation of the purpose or message

### Image Optimization

Before submitting images:
- Optimize PNG files to reduce file size without losing quality
- Tools like ImageOptim, TinyPNG, or pngquant can help
- Ensure transparency is preserved
- Test optimized images in the app

### Pull Request Review

Pull requests will be reviewed for:
- Adherence to design guidelines
- Technical correctness (proper JSON structure, file naming)
- Message appropriateness and sensitivity
- Image quality and optimization
- Overall contribution to the project's goals

## Code of Conduct

### Our Standards

- Be respectful and inclusive
- Focus on constructive feedback
- Remember this project supports a sensitive health topic
- Be patient with new contributors
- Prioritize the project's mission: promoting organ donation awareness

### Reporting Issues

If you experience any issues or have concerns:
- Open a GitHub issue for technical problems
- Contact maintainers privately for sensitive matters

## Questions?

If you have questions about contributing, please:
- Check existing issues and pull requests
- Review the README.md
- Open a new issue with your question

Thank you for helping make organ donation more visible and accessible through creative expression!
