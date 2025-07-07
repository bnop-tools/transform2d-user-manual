# Transform2D User Manual

This is the official user manual for Transform2D, a Unity tool for precise 2D GameObject positioning and alignment.

## Documentation

This documentation is built using [Retype](https://retype.com/), a modern static site generator.

### Building the Documentation

1. Install Retype:
   ```bash
   npm install retypeapp --global
   ```

2. Build the documentation:
   ```bash
   retype build
   ```

3. Serve locally for development:
   ```bash
   retype watch
   ```

### Deployment

The documentation is automatically deployed to GitHub Pages at: https://bnop-tools.github.io/transform2d-user-manual

#### Automatic Deployment
- Push changes to the `main` branch to trigger automatic deployment
- GitHub Actions will build the Retype site and deploy it to GitHub Pages
- Deployment typically takes 1-2 minutes

#### Manual Deployment
The documentation can also be deployed to any static hosting service. The built files are generated in the `.retype` directory when you run:
```bash
retype build
```

## Contributing

If you need to update the documentation, please edit the markdown files and rebuild using Retype.

## License

© Copyright 2025. All rights reserved.
