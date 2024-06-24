
class Media {
    void play() {
        print('Playing media...');
    }
}


class Song extends Media {

    String artist='monali thakor';
    Song(this.artist){
        print('$artist');
    }
    @override
    void play() {
        print('Playing Song by $artist...');
    }
}

void main() {

    Media m = Media();
    m.play();
    Song s = Song('Khola Janala');
    s.play();
}
