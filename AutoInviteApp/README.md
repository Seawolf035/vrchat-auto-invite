# VRChat Auto Invite — TGC Fork

This is Seawolf's maintained fork of **Titan_BCXR's VRChat Auto Invite launcher**.

## Credits

- **Original launcher:** Titan_BCXR
- **Later updates:** MILK & Ajaken365 for Site-19 usage
- **Further development:** Seawolf for The Gamer Club

Original upstream: https://github.com/TitanBCXR/vrchat-auto-invite

## Current TGC functionality

The current build retains the original inviter while adding file-based `usr_...` invites, current-instance inviting, separate logging, encrypted persistent VRChat sessions/2FA handling, the Pending Invite Recycler, and an optional Distributed Invite Node.

The optional Node can watch multiple VRChat instances on one PC, locally deduplicate and buffer sightings, submit them to a configured Google Apps Script relay using a revocable Node ID/key, use a relay-assigned Node Name, and request a Discord verification code. The Node does not use or transmit the parent inviter's VRChat account credentials/session and can run independently of the normal inviter/recycler.

See the included `V9`–`V14` update notes, `NODE_PLUGIN_QUICK_START.txt`, `PENDING_INVITE_RECYCLER_README.txt`, and `VRCX_STYLE_SESSION_README.txt` for details.

## Windows

Run `AutoInvite.bat`, or install `requirements.txt` and run `python main.py`.

Python 3.8+ is required.

## License

This fork retains the existing MIT license and original project attribution.
