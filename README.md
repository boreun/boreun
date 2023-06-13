// easyspaceutil.js
import { EasySpaceUtil } from 'easyspace'; // Animation library to manage space utilization https://github.com/thegrimsbotom/easyspace

// soundmanager.js and smsound.js (optional)
import SoundManager from './soundmanager';
const soundManager = new SoundManager();

// StorageManager.js
import StorageManager from './StorageManager';
export const storageUtils = new StorageManager({});

// GSAVE.js (optional)
if ('ServiceWorker' in navigator && Location.prototype.origin !== null) {
  const swRegistration = await navigator.serviceWorker.register('/');
}
<!-- Link to external assets -->
<link rel="icon" type="image/png" sizes="32x32" href="/images/icons/android-chrome-196x196.png" />
<link rel="stylesheet" href="/styles/reset.css" />
<link rel="stylesheet" href="/styles/app.css" />
<link rel="manifest" href="/manifest.json" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Flappy Bird - Score Board</title>

<!-- Load scripts -->
<script defer src="/scripts/app.js"></script>
<script defer src="/scripts/easyspace.js"></script>
<script defer src="/scripts/soundmanager.js"></script>
<script defer src="/scripts/GSAVE.js"></script>
