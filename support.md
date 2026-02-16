# MonoFlow — Support

Thank you for using MonoFlow! This page provides answers to common questions and guidance on how to get help.

---

## Getting Started

### What is MonoFlow?

MonoFlow is a modern flowchart and diagram editor for macOS. It features an infinite canvas, multiple node types, smart connection routing, and a built-in AI assistant that can create and modify diagrams based on natural language descriptions.

### System Requirements

- macOS 13.0 (Ventura) or later
- Apple Silicon or Intel Mac
- Internet connection required only for the AI assistant feature

---

## Frequently Asked Questions

### General

**Q: What file format does MonoFlow use?**  
A: MonoFlow saves diagrams as standard `.json` files. You can open, edit, and share these files freely.

**Q: Can I export my diagrams?**  
A: Yes. MonoFlow supports exporting diagrams to high-quality SVG format, which is ideal for presentations, documentation, and print.

**Q: Does MonoFlow require an internet connection?**  
A: No. You can create, edit, and save diagrams entirely offline. An internet connection is only needed when using the AI assistant feature.

**Q: Does MonoFlow collect my data?**  
A: No. All your diagram data is stored locally on your device. MonoFlow does not collect personal information, usage analytics, or telemetry of any kind. Please see our [Privacy Policy](privacy_policy.md) for full details.

### AI Assistant

**Q: How do I set up the AI assistant?**  
A: To use the AI assistant, you need to provide your own API key from a supported AI service provider. Open the AI chat panel, and you will be prompted to enter your API key. The key is stored securely in the macOS Keychain.

**Q: Which AI providers are supported?**  
A: MonoFlow currently supports Google Gemini. We plan to add support for additional providers in future updates.

**Q: Is my API key safe?**  
A: Yes. Your API key is stored in the macOS Keychain, which provides hardware-level encryption. The key is never sent to any server operated by us — it is used solely to communicate directly with your chosen AI provider.

**Q: What can the AI assistant do?**  
A: The AI assistant can:
- Create new nodes and connections based on your description
- Modify existing diagrams (rename, rearrange, delete nodes)
- Automatically lay out your flowchart
- Interpret images and screenshots into structured diagrams

**Q: Are my AI conversations private?**  
A: Yes. Your messages are sent directly from your device to the AI provider's servers using your personal API key. MonoFlow does not operate any intermediary server and has no access to your conversations.

### Canvas & Editing

**Q: How do I zoom in and out?**  
A: Hold ⌘ (Command) and scroll with the mouse wheel or trackpad to zoom. The zoom range is 25% to 100%.

**Q: How do I pan the canvas?**  
A: Click the pan mode button (✋ hand icon) in the toolbar to enter pan mode, then drag the canvas. You can also use the middle mouse button to pan at any time.

**Q: How do I select multiple nodes?**  
A: Click and drag on an empty area of the canvas to draw a selection box. You can also hold Shift and click individual nodes to add them to your selection.

**Q: How do I undo or redo an action?**  
A: Use the standard keyboard shortcuts: ⌘Z to undo and ⇧⌘Z to redo. MonoFlow maintains a full history of your actions.

**Q: What are Predefined Components?**  
A: Predefined Components are special container nodes that allow you to group related nodes into collapsible, reusable sub-diagrams. They help organize complex flowcharts and keep your canvas clean.

**Q: How do I connect two nodes?**  
A: Click the link button on a node, or use the connection mode. Then click on the target node to create a connection. You can also configure port directions (top, bottom, left, right, or auto) for each connection.

**Q: How does auto-save work?**  
A: When you open or save a file, auto-save activates automatically. MonoFlow periodically saves your work to the same file location to prevent data loss.

### Troubleshooting

**Q: The AI assistant is not responding.**  
A: Please check the following:
1. Ensure your API key is correctly entered
2. Verify your internet connection is active
3. Confirm your API key has sufficient quota/credits with your AI provider
4. Try clearing the conversation history and starting a new chat

**Q: My diagram file won't open.**  
A: MonoFlow opens `.json` files in its own format. Ensure the file has not been corrupted or modified by another application. If the file was created with an older version of MonoFlow, it should still be compatible.

**Q: Nodes or connections look misaligned.**  
A: Try using the auto-layout feature to rearrange your diagram. You can also manually snap nodes to the grid by dragging them.

**Q: The app feels slow with a large diagram.**  
A: For very large diagrams with many nodes, consider:
- Collapsing Predefined Components you're not actively editing
- Using the grid toggle to reduce visual complexity
- Breaking complex diagrams into separate files

---

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| ⌘Z | Undo |
| ⇧⌘Z | Redo |
| ⌘C | Copy selected nodes |
| ⌘X | Cut selected nodes |
| ⌘V | Paste nodes |
| ⌘A | Select all nodes |
| ⌫ / Delete | Delete selected nodes or connection |
| ⌘ + Scroll | Zoom canvas in/out |
| Middle mouse + Drag | Pan the canvas |

---

## Contact Us

If you need further assistance or want to report a bug, please reach out to us:

**Email:** ben97.work@gmail.com

We typically respond within 48 hours.

---

## Version History

### Version 1.0.0
- Initial release
- Infinite zoomable canvas with snap-to-grid
- 8 node types: Process, Decision, Terminator, Data, Predefined Component, Annotation, Connector, Object
- Smart connection routing with configurable ports
- AI assistant powered by Google Gemini
- SVG export
- Auto-layout engine
- Undo/redo history
- Auto-save
- Two color themes: Default and Black & White

---

*Last updated: February 16, 2026*
