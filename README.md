# email-event-extractor

The application will continuously monitor your inbox for new emails, extract event information, and generate ICS files in the same directory.

## Project Structure

- `app.py`: The main application file that coordinates the other modules
- `email_receiver.py`: Handles email connectivity and retrieval
- `event_extractor.py`: Extracts event details from email content
- `ics_generator.py`: Generates ICS files from extracted event data

## Customization

- Modify the email parsing logic in `event_extractor.py` to match your specific email formats
- Adjust the ICS file generation in `ics_generator.py` to include additional event details if needed
- Update the email checking interval in `app.py` (currently set to 5 minutes)

## Security Note

This application requires your email credentials. It's recommended to use app-specific passwords or OAuth for enhanced security. Never share your email credentials or commit them to version control.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).