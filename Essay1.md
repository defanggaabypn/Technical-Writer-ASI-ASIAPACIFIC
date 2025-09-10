# Algoritma Mengoperasikan Sepeda Ontel/Kayuh

## Pseudocode
```
START
    // Persiapan sebelum mengendarai
    Periksa kondisi sepeda (ban, rem, rantai)
    IF kondisi sepeda tidak baik THEN
        Perbaiki bagian yang rusak
    END IF

    Sesuaikan ketinggian sadel
    Pastikan berdiri di samping sepeda

    // Naik ke sepeda
    Pegang setang dengan kedua tangan
    Letakkan satu kaki pada pedal di posisi atas
    Dorong tubuh ke depan dengan kaki yang masih di tanah

    // Mulai mengayuh
    Tekan pedal ke bawah dengan kaki yang sudah di pedal
    Angkat kaki yang masih di tanah ke pedal lainnya

    // Menjaga keseimbangan dan mengendarai
    WHILE ingin terus bersepeda DO
        Kayuh pedal secara bergantian
        Gunakan setang untuk mengarahkan sepeda

        IF ingin berbelok ke kanan THEN
            Putar setang ke kanan
        ELSE IF ingin berbelok ke kiri THEN
            Putar setang ke kiri
        END IF

        IF ingin mengurangi kecepatan THEN
            Kurangi kecepatan mengayuh
            IF perlu berhenti cepat THEN
                Tekan rem
            END IF
        END IF
    END WHILE

    // Berhenti
    Kurangi kecepatan mengayuh
    Tekan rem perlahan
    Ketika hampir berhenti, turunkan satu kaki ke tanah
    Turun dari sepeda
END
```

## Flowchart
```mermaid
flowchart TD
    A[Mulai] --> B[Periksa kondisi sepeda]
    B --> C{Kondisi baik?}
    C -->|Tidak| D[Perbaiki bagian yang rusak]
    D --> E[Sesuaikan ketinggian sadel]
    C -->|Ya| E
    E --> F[Berdiri di samping sepeda]
    F --> G[Pegang setang dengan kedua tangan]
    G --> H[Letakkan satu kaki pada pedal di posisi atas]
    H --> I[Dorong tubuh ke depan dengan kaki yang di tanah]
    I --> J[Tekan pedal ke bawah]
    J --> K[Angkat kaki yang masih di tanah ke pedal lainnya]
    K --> L[Kayuh pedal secara bergantian]
    L --> M{Ingin berbelok?}
    M -->|Ya| N{Arah belok?}
    N -->|Kanan| O[Putar setang ke kanan]
    N -->|Kiri| P[Putar setang ke kiri]
    O --> Q{Ingin mengurangi kecepatan?}
    P --> Q
    M -->|Tidak| Q
    Q -->|Ya| R[Kurangi kecepatan mengayuh]
    R --> S{Perlu berhenti cepat?}
    S -->|Ya| T[Tekan rem]
    S -->|Tidak| U{Ingin terus bersepeda?}
    Q -->|Tidak| U
    T --> U
    U -->|Ya| L
    U -->|Tidak| V[Kurangi kecepatan mengayuh]
    V --> W[Tekan rem perlahan]
    W --> X[Turunkan satu kaki ke tanah]
    X --> Y[Turun dari sepeda]
    Y --> Z[Selesai]
```
