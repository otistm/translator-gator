# Game Translator App

A real-time translation tool interface designed for mobile gamers playing titles in foreign languages (CN/JP/KR). This component features a modern, dark-themed UI with permission flows, language configuration, and overlay simulation.

## Features

- **Translation Control**: One-tap start/stop mechanism with visual feedback
- **Permission Management**: Interactive flow for requesting critical system permissions (Overlay, Screen Recording)
- **Language Selection**: Configurable source and target languages
- **Overlay Simulation**: accurate representation of the floating translation bubble
- **Game Launcher**: Tabbed interface for managing games

## Dependencies

- `framer-motion`: For smooth transitions and animations
- `lucide-react`: For iconography
- `clsx` & `tailwind-merge`: For dynamic class handling

## Usage

```tsx
import { GameTranslatorApp } from '@/sd-components/b85ff93e-a16b-4184-b778-7eccd4bdb653';

function MyPage() {
  return (
    <div className="h-screen w-full">
      <GameTranslatorApp />
    </div>
  );
}
```

## Props

The component currently manages its own state for demonstration purposes and accepts no required props.
