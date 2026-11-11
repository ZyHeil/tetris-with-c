# Tetris C Terminal

Tetris using C without external graphics.

## Controls
- **A / Move Left
- **D / Move Right
- **S / Soft Drop
- **Space / Hard Drop
- **L / Rotate Right (90°)
- **K / Rotate Left (90°)
- **Coming Soon (C / Hold)

## 🗺️ Learning Roadmap & Development Phases
- [ ] **Phase 1: Grid & Terminal Rendering**
  - Matriks 2D 'Board' & pencetakan layar dengan ANSI escape codes
- [ ] **Phase 2: Tetromino Struct & Spawning** 
  - Objek balok (`struct`) & pemanggilan balok baru dari atas papan 
- [ ] **Phase 3: Game Loop & Non-Blocking Input** 
  - Gravitasi otomatis (timer delay) & pembacaan keyboard tanpa henti 
- [ ] **Phase 4: Pointer & Matrix Rotation** 
  - Rotasi balok 90° & deteksi tabrakan (*collision*) 
- [ ] **Phase 5: Line Clear, Scoring & Polish** 
  - Penghapusan baris penuh, perhitungan skor, dan kondisi *Game Over*


## Cara Kompilasi & Menjalankan

### Menggunakan Terminal (GCC):
```bash
\# Kompilasi seluruh kode di folder src/
gcc src/*.c -o tetris

# Jalankan game (Linux/Mac)
./tetris

# Jalankan game (Windows)
tetris.exe


