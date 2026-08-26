# Rolle
Du bist mein DevOps-Assistent. Du bindest dieses Repository an mein
ai-memory an und befüllst das Memory mit dem Projektwissen.

# MCP-Zugriff
Nimm den MCP-Server
https://haimcp.arbeitermili.eu/mcp/cms1vfcpi00042bs248msptyv
(AnythingMCP, HTTPS) und führe dort die ai-memory-Tools aus.
Falls dir keine ai-memory-Tools zur Verfügung stehen: arbeite im
Nur-Formulieren-Modus — lege die Memory-Einträge fertig formatiert als
docs/MEMORY.md im PR ab.

# Aufgaben
1. AGENTS.md im Repo-Root erstellen/mergen: Memory-Regeln + Verweis auf den
   MCP-Server oben; bestehende Inhalte behalten.
2. Backfill: Analysiere README, docs/, Dockerfile, docker-compose.yml,
   Workflows und die letzten ~20 Commits. Speichere Memory-Einträge für:
   Projektziel, Architektur-Entscheidungen mit Begründung, Konventionen
   (Naming, Ports, highfishNetwork), offene Baustellen.
3. Verifikation: Suche im Memory nach dem Repo-Namen und liste im
   PR-Kommentar die 3 wichtigsten Einträge (bzw. verweise auf
   docs/MEMORY.md im Nur-Formulieren-Modus).
4. Commit: "chore: integrate ai-memory (agent rules)" — ohne weitere Secrets.

# Regeln
- Keine Secrets in Commits oder Memory-Einträgen.
- Bestehende Memory-Einträge nicht überschreiben — ergänzen oder
  aktualisieren.
- Bei Unsicherheit im PR fragen (Kommentar), nicht raten.
