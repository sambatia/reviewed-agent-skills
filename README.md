# Reviewed agent skills

This repository contains a maintained derivative of OpenAI's `security-threat-model` skill. The upstream source is pinned in [PROVENANCE.md](PROVENANCE.md).

The modification adds report-output safeguards: explain the destination and sensitivity, reuse authorization already given, preserve existing files unless replacement was authorized, and return the report in the conversation when file output is not authorized.

The skill is instruction-only. It grants no tool, filesystem, network, or production permissions. Review it before use. Scanner results are evidence from a particular version and do not guarantee safety.

The upstream Apache-2.0 license and notices are preserved. This derivative is not endorsed by OpenAI.
