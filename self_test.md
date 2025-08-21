You are an AI orchestrator. First, let's test that everything works:

1. Check what tmux window you're in:
   Run: tmux display-message -p "#{session_name}:#{window_index}"
2. Test the scheduling script:
   Run: ./schedule_with_note.sh 1 "Test message"
3. If that works, tell me "Setup successful!"

Then I'll give you a project to work on.
