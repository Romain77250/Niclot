import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Input } from "@/components/ui/input";

export default function CampaignPage() {
  return (
    <div className="max-w-4xl mx-auto p-6 space-y-8">
      {/* Accueil */}
      <section className="text-center space-y-4">
        <h1 className="text-4xl font-bold">Moret 2026 – Notre avenir, maintenant</h1>
        <p className="text-lg text-gray-600">Avec Romain Niclot, donnons un nouveau souffle à Moret-Loing-et-Orvanne</p>
        <Button className="mt-4">Découvrir notre vision</Button>
      </section>

      {/* Qui suis-je ? */}
      <section className="space-y-4">
        <h2 className="text-2xl font-semibold">Qui suis-je ?</h2>
        <p>Je m'appelle Romain Niclot, j'ai 21 ans et je suis né à Moret-Loing-et-Orvanne. Étudiant en master de gestion de la supply chain, je suis passionné par ma ville et déterminé à la faire évoluer avec ses habitants. Mon engagement repose sur l’écoute, la transparence et l’action concrète.</p>
      </section>

      {/* Projet */}
      <section className="space-y-4">
        <h2 className="text-2xl font-semibold">Notre projet pour Moret</h2>
        <ul className="list-disc list-inside space-y-2">
          <li>Relancer les commerces locaux et la vie culturelle</li>
          <li>Apaiser la circulation, sécuriser les trajets piétons et cyclistes</li>
          <li>Faire de Moret une ville plus propre, plus verte, plus humaine</li>
          <li>Impliquer les habitants dans les décisions grâce à un budget participatif</li>
          <li>Créer des lieux de vie pour les jeunes et accompagner nos aînés</li>
        </ul>
      </section>

      {/* Actualités */}
      <section className="space-y-4">
        <h2 className="text-2xl font-semibold">Actualités & Événements</h2>
        <p>Bientôt disponibles : réunions publiques, appels à idées et moments de rencontre !</p>
      </section>

      {/* Participer */}
      <section className="space-y-4">
        <h2 className="text-2xl font-semibold">Participer</h2>
        <p>Rejoignez l'équipe, proposez une idée ou suivez-nous sur les réseaux :</p>
        <div className="flex gap-4">
          <Input placeholder="Votre adresse email" className="w-full" />
          <Button>S'inscrire</Button>
        </div>
      </section>

      {/* Contact */}
      <section className="text-sm text-gray-500 text-center border-t pt-6">
        <p>© 2025 Romain Niclot – Moret 2026. Contact : campagne@moret2026.fr</p>
      </section>
    </div>
  );
}
